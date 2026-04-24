# multiplayer-fabric-casync-seed

Content-addressed chunk store for multiplayer-fabric zone server ELF programs.

Built with `mix aria_storage.make` from `aria-storage`.

## Fetch an ELF

```sh
cd multiplayer-fabric/aria-storage
mix aria_storage.fetch \
  --index https://raw.githubusercontent.com/V-Sekai/multiplayer-fabric-casync-seed/main/taskweft_planner.caibx \
  --store https://raw.githubusercontent.com/V-Sekai/multiplayer-fabric-casync-seed/main/store \
  --output /tmp/elfs
```

## Contents

| Index | Description |
|-------|-------------|
| `taskweft_planner.caibx` | Taskweft HTN planner + HRR memory (RISC-V ELF for godot-sandbox) |
