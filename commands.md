1. Build docker:  `docker build .`
2. Build docker image: `docker-compose build`
3. Run **flake8**: `docker-compose run --rm app sh -c "flake8"`
4. Run **django** and start project: `docker-compose run --rm app sh -c "django-admin startproject app ."`
5. Start the server through docker: `docker-compose up`
6. Test code inside app folder: `python app/manage.py test`
7. Run the test through docker compose `docker-compose run --rm app sh -c "python manage.py test"`