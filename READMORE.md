start docker wit image
docker run -dp 5005:5000 -w /app -v "$(pwd):/app" image_name

docker build -t name . //==>> <<    >> <<==//