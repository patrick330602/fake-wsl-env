# Fake WSL environment

A fake WSL environment for preforming WSL specific tasks in Docker or CI.

<https://hub.docker.com/r/patrick330602/fake_wsl_env/>

To download the image, run `docker pull patrick330602/fake_wsl_env`

To build locally, clone the repo and run `docker -t <whatever-the-name-you-want> .` in the folder.

## Why?

**Why not?**

Well, because there is currently not a good way to test WSL-related projects on most CI, since:

- Windows Server Docker do not support installing WSL feature(asks for reboot but will hang on reboot);
- All CIs do not provide WSL support, including AppVeyor([Issue #1295](https://github.com/appveyor/ci/issues/1295)).

## License

LGPL v 3.0.