# redm-server-data-cfx

Local copy of the official CFX server data repository used as the base resource layer for RedM server infrastructure.

Original upstream repository:

https://github.com/citizenfx/cfx-server-data

## Purpose

This repository provides a stable and reproducible base set of RedM/FiveM server resources.

It exists to:

- avoid dependency on external repository availability
- provide controlled infrastructure updates
- preserve reproducible server environments
- separate official base resources from custom project resources

## Repository Structure

```text
[gamemodes]
[gameplay]
[local]
[managers]
[standalone]
[system]
[test]
```

### Directory Description

| Directory | Purpose |
|---|---|
| `[gamemodes]` | Base gamemode resources |
| `[gameplay]` | Gameplay-related base resources |
| `[local]` | Local-only temporary resources |
| `[managers]` | Session and server management resources |
| `[standalone]` | Standalone utility resources |
| `[system]` | Core system resources |
| `[test]` | Testing and experimental resources |

## Usage

Clone the repository instead of downloading ZIP archives.

```bash
git clone https://github.com/Trembita-Games/redm-server-data-cfx.git
```

## Update Policy

Changes in this repository should be limited to:

- upstream synchronization
- compatibility fixes
- infrastructure fixes
- documentation updates

Custom gameplay or project-specific resources should not be added here.

## License

This repository contains content originating from:

https://github.com/citizenfx/cfx-server-data

Refer to the original upstream repository for licensing details.
