Install this MCP server by adding the following JSON code to your JSON config file:

```json
{
    "mcpServers": {
        "chess-server": {
            "command": "uvx",
            "args": [
                "--from",
                "git+https://github.com/aharrison-git/MCP-Build-Chess-Server.git",
                "chess"
            ]
        }
    }
}

`