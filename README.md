# Qhapaq

> NK

```bash
# install ruby gems
docker-compose run sinatra bundle install --path vendor/bundle --without production

# create postgres databese table
docker-compose run sinatra bundle exec rake db:create

# database migrate
docker-compose run sinatra bundle exec rake db:migrate

# install init data
docker-compose run sinatra bundle exec rake db:seed

# start
docker-compose up
```
