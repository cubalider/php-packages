# Setup

git clone https://github.com/yosmy/php-packages

docker network create php_packages

cd php-packages

docker-compose -f docker/all.yml -p php-packages up -d --remove-orphans

# Rebuild

rebuild yosmy/payment
