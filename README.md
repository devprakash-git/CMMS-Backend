#In Settings.py all SECURE_SSL feilds are false for production purposes we will need to change it to true for deployment.

You will need following .env variables for running this:

SECRET_KEY_SETTINGS = "your-secret-key"
SECURE = "False"
SAMESITE = "Lax"
BREVO_API_KEY="your-brevo-api-key"
DEBUG="True"
EMAIL_HOST_USER="your-email"

