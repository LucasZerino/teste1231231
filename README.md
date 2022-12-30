1 - rm -rf ./wppconnect-chatwoot/data


2 - mkdir ./wppconnect-chatwoot/data


3 - ./wppconnect-chatwoot/data/postgres


4 - ./wppconnect-chatwoot/data/redis


5 - docker compose up --build --no-start


6 - docker-compose run --rm rails bundle exec rails db:chatwoot_prepare


7 - docker compose up -d