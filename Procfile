# Puma server config
web: bundle exec puma -t 5:5 -p ${PORT:-3000} -e ${RACK_ENV:-development}

# Generate config file
web: bundle exec puma -C config/puma.rb
