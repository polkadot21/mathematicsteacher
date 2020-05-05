# Math teacher Web app
## landing page
This web-site is a landing page for a math teacher.

This site allows to add a paypal button to collect money for lessons.

## Launching the development environment
You need to have Python and PostgreSQL installed
``` bash
git clone https://github.com/hmlON/mun.git
cd mun

pip install -r requirements.txt

createuser -s postgres
createuser -s mun
createdb -U postgres mun

python manage.py runserver
```

## How you can contribute
- support for more integrations with music services (e.g. Apple Music)
- support for more notifications (e.g. Facebook Bot)
- forwarding from HTTP to HTTPS
- fetching checker
- add ability to have an account without an integration
- improve design
- add tests
- refactoring
