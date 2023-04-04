# GLaDOS

GLaDOS is an Alpine Linux profile with a focus on robotics, made for a school project, named after Portal's AI antagonist.
At the moment, it targets Raspberry Pis, might add support for Pine64 SBCs as well.

## Testing & development

- Follow the [Alpine Linux Wiki's guide on custom ISOs](https://wiki.alpinelinux.org/wiki/How_to_make_a_custom_ISO_image_with_mkimage)
- Copy the `mkimg.glados.sh` into `/path/to/aports/scripts`
- Test with `./mkimage.sh --arch aarch64 --profile glados --outdir /home/build/iso --repository https://dl-cdn.alpinelinux.org/alpine/v3.17/main`
