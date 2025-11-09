"firebase": {
      "command": "npx",
      "args": [
        "firebase-tools@latest",
        "experimental:mcp",
        "--dir",
        "/mnt/c/Users/Shaban/Documents/firebase_mcp"
      ]
    },
    ```
3.  and then try `npx -y firebase-tools@latest experimental:mcp`
4.  if you see error googleapis not found then run command : npm install firebase-tools googleapis
5.  create folder by `mkdir foldername` and `cd` to that folder and run `firebase login` and `firebase init`
6.  choose existing project and complete steps
7.  run gemini and you are ready to go
