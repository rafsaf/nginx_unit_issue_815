nginx unit issue https://github.com/nginx/unit/issues/815

1. build `unit:1.30.0-python3.10` and `unit:1.30.0-python3.11` docker images, see https://github.com/nginx/unit/issues/815#issuecomment-1419366256 

2. `docker-compose -f docker-compose.dev.yml up -d --build` changing Dockerfile and nginx-unit-config.json if needed 