# Example build command

```
# Create builder
docker buildx create --use --name m1_builder

# Check builder status
docker buildx inspect --bootstrap

# Build and Push
docker buildx build --platform linux/amd64,linux/arm64 --push -t tig4605246/ubuntu_util:0.3 .

```