# Caddy Docker build with Porkbun DNS

This image is updated automatically by GitHub Actions when a new version of [Caddy](https://github.com/caddyserver/caddy) is released using the official [Caddy Docker](https://hub.docker.com/_/caddy) image and the following modules:
- [**Porkbun DNS**](https://github.com/danielkinahan/caddy-custom-builds?tab=readme-ov-file#dns-modules): for Porkbun DNS-01 ACME validation support | [caddy-dns/porkbun](https://github.com/caddy-dns/porkbun)

## Usage

Since this image built off the official Caddy Docker image, the same [volumes](https://docs.docker.com/storage/volumes/) and/or [bind mounts](https://docs.docker.com/storage/bind-mounts/), ports mapping, etc. can be used with this container. Additional [environment variables](https://caddyserver.com/docs/caddyfile/concepts#environment-variables) may be needed for the added modules. Please, refer to the repository's [README](https://github.com/danielkinahan/caddy-custom-builds?tab=readme-ov-file#container-creation) file for further usage instructions.

Docker builds for all Caddy supported platforms available at the following container registries:
- [**Docker Hub**](https://hub.docker.com/r/danielkinahan/caddy-porkbun) `docker pull danielkinahan/caddy-porkbun:latest`
- [**GitHub Packages**](https://ghcr.io/danielkinahan/caddy-porkbun) `docker pull ghcr.io/danielkinahan/caddy-porkbun:latest`
- [**Quay**](https://quay.io/danielkinahan/caddy-porkbun) `docker pull quay.io/danielkinahan/caddy-porkbun:latest`

### Tags

The following tags are available for the `danielkinahan/caddy-porkbun` image:

- `latest`
- `<version>` (eg: `2.7.4`, including: `2.7`, `2`, etc.)

## Contributing

Feel free to contribute, request additional Caddy images with your preferred modules, and make things better by opening an [Issue](https://github.com/danielkinahan/caddy-custom-builds/issues) or [Pull Request](https://github.com/danielkinahan/caddy-custom-builds/pulls).

## License

Software under [GPL-3.0](https://github.com/danielkinahan/caddy-custom-builds/blob/main/LICENSE) ensures users' freedom to use, modify, and distribute it while keeping the source code accessible. It promotes transparency, collaboration, and knowledge sharing. Users agree to comply with the GPL-3.0 license terms and provide the same freedom to others.