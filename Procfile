web: cd backend && php artisan serve --host=0.0.0.0 --port=${PORT}
build-frontend: cd frontend && npm install && npm run build
web: heroku-php-apache2 public/
