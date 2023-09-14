# Dev Container
## 手順
- 作業フォルダに.devcontainerのファルダを作る
- devcontainer.jsonに設定を書き込む

```json
{
    "name": "web-container",
    "service": "web",
    "dockerComposeFile": "../../docker-compose.yml",
    "workspaceFolder": "/workspace",
    "customizations": {
        "vscode": {
            "extensions": [
                "firsttris.vscode-jest-runner"
            ]
        }
    }
}
```
