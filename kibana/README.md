## x86_64
docker buildx build --platform linux/amd64 --build-arg ARCH=x64 -t tag-x86_64 .

## arm64
docker buildx build --platform linux/arm64 --build-arg ARCH=arm64 -t tag-arm64 .