# react-avancado-api

Strapi backend for react avançado course

docker run \
  --name postgres \
  -e POSTGRES_USER=strapi \
  -e POSTGRES_PASSWORD=strapi \
  -e POSTGRES_DB=strapi \
  -p 5432:5432 \
  -d \
  postgres