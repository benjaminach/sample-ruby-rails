web: bundle exec rails server -b 0.0.0.0 -p $PORT -e $RAILS_ENV
worker: bundle exec rake jobs:work || tail -f /dev/null
