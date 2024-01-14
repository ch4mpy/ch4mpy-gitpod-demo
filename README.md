# ch4mpy-gitpod-demo
Sample repo to try running an OAuth2 client on Gitpod

Here is the content of the `.vscode/launch.json` setting the OAuth2 client secret:
```json
{
    "configurations": [
        {
            "type": "java",
            "name": "Spring Boot-GitpodDemoApplication<oauth2-client-with-authorization-code>",
            "request": "launch",
            "cwd": "${workspaceFolder}",
            "mainClass": "com.c4soft.gitpoddemo.GitpodDemoApplication",
            "projectName": "oauth2-client-with-authorization-code",
            "args": "--issuer=change-me --client-id=with-your-auth0-instance --client-secret=values",
            "envFile": "${workspaceFolder}/.env"
        }
    ]
}
```
