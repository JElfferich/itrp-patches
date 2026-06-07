# IterationRP Patches

## Features

- OpenDRT display rendering transform (tonemapping) by [Jed Smith](https://github.com/jedypod/open-display-transform) for polished and rich color rendering.
- More in the future.

## How to apply
Requirements for Windows:
- [Git](https://git-scm.com/install/windows)

```bash
# If on Windows run the commands with Git Bash.
git clone https://github.com/JElfferich/itrp-patches.git
cd itrp-patches
# Extract IterationRP to itrp-patches folder and then edit and run the command below.
patch -p1 -d <itrp_folder_name> < itrp.patch
```

## License
[GPLv3](https://github.com/JElfferich/itrp-patches/blob/main/LICENSE)
