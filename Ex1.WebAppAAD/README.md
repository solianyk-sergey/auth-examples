# Ex1.WebAppAAD

This is implementation of the WebApplication that requires authentication in the Azure Active Directory.

`AddMicrosoftIdentityWebApp` method is used to configure communication with the AAD. `/Home/Claims` page requires user
authentication and displays user claims.

`ClientId`, `ClientSecret` and `TenantId` are not stored in the git repo. Please create AAD application with a secret and use values
from the real instance before running this app locally.

## Udemy Example Link:
https://www.udemy.com/course/practical-oauth-openid-and-jwt-in-c-net-core/learn/lecture/28836252#overview