# api-quick-start

Template Project for starting up CRUD API with Django Rest Framework

## Customization Steps

- DO NOT migrate yet
- add additional dependencies as needed
  - Re-export requirements.txt as needed
- change `cookiestands` folder to the app name of your choice
- Search through entire code base for `CookieStand`,`CookieStands` and `cookiestands` to modify code to use your resource
  - `project/settings.py`
  - `project/urls.py`
  - App's files
    - `views.py`
    - `urls.py`
    - `admin.py`
    - `serializers.py`
    - `permissions.py`
- Update CookieStandModel with fields you need
  - Make sure to update other modules that would be affected by Model customizations. E.g. serializers, tests, etc.
- Rename `project/.env.sample` to `.env` and update as needed
- Run makemigrations and migrate commands
- Optional: Update `api_tester.py`
