zzz: bundle exec rake jobs:work1 || tail -f /dev/null
worker: bundle exec rake jobs:work2 || tail -f /dev/null
web: bundle exec rails server -b 0.0.0.0 -p $PORT -e $RAILS_ENV
aaa: bundle exec rake jobs:work3 || tail -f /dev/null
