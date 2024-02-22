# Class 34 Notes API Deployment

## Why is this important?

- Understanding the best practices will allow your code to be more readable to other devs.

- White Noise ensures you don't have to sacrifice performance to benefit from simplicity

- CORS prevents malicious websites from spamming your API with requests.

## Reading Questions

1. The key principles to follow when organizing your Django settings are keep settings in environment variables, write default values for production config, don't hardcode sensitive settings, split settings into groups and follow naming conventions.  [source](https://djangostars.com/blog/configuring-django-settings-best-practices/)

2. The White Noise library makes your application a self-contained unit that can be deployed anywhere without other external services [source](https://whitenoise.readthedocs.io/en/stable/).To integrate White Noise first you install it: `pip install whitenoise`.  You then add the middleware into the middleware section of `settings.py`, ensure it is below the `.SecurityMiddleware` and before the others.

3. CORS is a middleware that restricts how resources can be requested from another domain.  It's used to prevent malicious websites from accessing data from your site.  It can be implemented through middleware by installing the cors-headers and adding the CorsMiddleware as high as possible in the middleware section of settings.py.  You can then add allowed origins that can make requests to your API.  

## Things I want to know more about?

- N/A
