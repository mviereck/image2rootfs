# image2rootfs
Create a rootfs tarball from a Docker image

Pulls an image and creates a tarball at `/tmp/image2rootfs/rootfs-<image-name>.tar`.
Pulls from Docker hub by default or from elsewhere specified with 
skopeo image name syntax (see `man skopeo`, section `IMAGE NAMES`).

## Syntax: 
```
image2rootfs [OPTIONS] IMAGENAME
```
  
## Options:
```
  -h, --help
  -v, --verbose
      --version
```
## Dependencies:
```
  skopeo
  python|python3
  tar
  gzip
  file
```
