

## run dev docker file
docker build -f Dockerfile.dev .

### port mapping
docker run -p 3000:3000 <id>

## run test without docker-compose up

doceker exec -it <id> sh

=> npm run test
