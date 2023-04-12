# handbook-vscode-debug-nestjs

an example code for visual studio code settings to execute the current file with Jest.

```json
{
  "version": "0.2.0",
  "configurations": [
    {
      "command": "npx jest ${fileBasename}",
      "name": "Jest: Current File",
      "request": "launch",
      "type": "node-terminal",
      "cwd": "${workspaceFolder}"
    }
  ]
}
```

lanunch.json
