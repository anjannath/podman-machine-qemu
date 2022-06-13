### Naming convention

Name every release as `podman-machine-qemu-<qemu-version>-<build-tag>`
Name the `QEmu` distributable archives as `podman-machine-qemu-<arch>-<version>.tar.xz` where version is `<qemu-version>-<build-tag>`

### Creating a new release
2. Create a tag named as <qemu-version>-<build-number>, e.g `6.2.0-1` the next build using the same QEmu version will have tag `6.2.0-2`
3. Build and publish the generated artifacts. (look at the [README](./README.md) for instructions to build)
