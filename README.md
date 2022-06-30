# custom-user-app
###### A Django app with email login instead of username.

This is Django app which extends the **AbstractBaseUser model**, and overwrites the username login for email login.


#### How To Use The App.

```
1. Pull repo into your django project.
2. Add **AUTH_USER_MODEL = 'accounts.Account'** in your **settings.py** file ( under WSGI_APPLICATION line.)
3. Still in your **settings.py** file, add the app in installed apps.
4. Add the app urls in **urls.py** file.
5. The run ** python manage test ** in your terminal, the tests should fail since i didnt include the templates. Debug those to apply yourself.

```