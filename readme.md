# Steps to Connect MCP in Gemini CLI in WSL

```json
"firebase": {
  "command": "npx",
  "args": [
    "firebase-tools@latest",
    "experimental:mcp",
    "--dir",
    "/mnt/c/Users/Shaban/Documents/firebase_mcp"
  ]
}
```

Then try `npx -y firebase-tools@latest experimental:mcp`
If you see error `googleapis not found` then run command: `npm install firebase-tools googleapis`
Create folder by `mkdir foldername` and `cd` to that folder and run `firebase login` and `firebase init`
Choose existing project and complete steps
Run `gemini` and you are ready to go