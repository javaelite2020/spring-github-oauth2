# spring-github-oauth2
Sample Spring Boot project for OAuth2 login with GitHub


# How to create GitHub app for OAuth2 authentication
1. Login to GitHub
2. Goto Settings --> Developer Settings
3. Click on 'New GitHub App'
4. Fill the details
5. Callback url would be http://localhost:8080/login/oauth2/code/github for local testing when using spring security
6. We can uncheck Webhook url
7. Select User permissions (Email address and Profile)
8. Select Any Account radio button
9. Click on 'Create GitHub App'
10. Copy the Client ID and Client Secret to map it application.yml
