# Class 29 Notes Django Custom User

## Why is this important?

- Custom User Models provide flexibility and control over the user fields inside of an application.

- DjangoX sounds great if it will the setup time needed.

## Reading Questions

1. The key benefits of using a Django Custom User Model are flexibility and control over user information.  It differs from the default Django User Model by allowing the ability to remove undesired user fields or add your own.

2. To create a Custom User Model you must add the `accounts` app to `settings.py` and use the `AUTH_USER_MODEL` so Django knows to use the Custom User Model.  Then you create a Custom User Model class in `models.py`.  Finally you update `admin.py` to recognize your custom user instead of the default user. [source](https://learndjango.com/tutorials/django-custom-user-model)

3. DjangoX is a project template for Django that can include Custom User Models and third party integrations.  It seems like DjangoX does everything that we had to do in the last few days for us, including pre installed packages like tailwind and structures the project for us.  DjangoX provides us with a template allow us to focus on the unique aspects of our projects.  An example would be setting up a premade authentication panel for users to sign in on allowing them to use our application

## Things I want to know more about

- Is there a way to automate the entire project setup with DjangoX