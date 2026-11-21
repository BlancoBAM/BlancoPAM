# OrangePi 4 Pro — Image Builder

Automated GitHub Actions build for the **Orange Pi 4 Pro** (Allwinner A733 / `sun60iw2`).

| | |
|---|---|
| **OS** | Ubuntu 26.04 LTS Resolute |
| **Desktop** | Xfce (minimal base) |
| **Kernel** | Linux 6.18.y mainline + [A733 patches](https://github.com/jonas5/Allwinner-A733-kernel) |
| **Build harness** | [orangepi-xunlong/orangepi-build](https://github.com/orangepi-xunlong/orangepi-build) |

## Usage

1. Go to **Actions → Build OrangePi 4 Pro Image → Run workflow**
2. Leave defaults or customise the release/flavour inputs
3. Wait ~90 min for the build to complete
4. Download the `.img.xz` from the **Releases** tab
5. Flash with [Armbian Imager](https://www.armbian.com/download/) to your SD card

## Default credentials (first boot)

| User | Password |
|---|---|
| `orangepi` | `orangepi` |
| `root` | `orangepi` |

SSH is pre-enabled on port 22. The root partition auto-expands on first boot.
