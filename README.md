1- head over to https://www.npmjs.com/package/keycloak-angular and work through the instructions to install the keycloak-angular library

2- place the silent-check-sso.html file in the public folder of your angular project
then 
"assets": [
  {
    "glob": "**/*",
    "input": "public",
    "output": "/assets"
  }
]

3- make sure to work with ["roles"]  here     const requiredRoles = route.data['roles']; because the data is defined using an index signature.

4- make sure to add valid redirectUri and also web origins in keycloak interface"# ecom-angular-keycloak" 
