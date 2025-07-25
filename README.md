./mvnw clean package
docker build -t recipes-api .
docker run -p 8081:8081 recipes-api
