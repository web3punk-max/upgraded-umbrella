   ```json
   {
     "name": "Ubuntu 22.04 Codespace",
     "image": "ubuntu:22.04",
     "postCreateCommand": "sudo apt-get update && sudo apt-get install -y build-essential",
     "extensions": [
       "ms-vscode.cpptools",
       "ms-python.python",
       "ms-vscode.csharp"
     ]
   }