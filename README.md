# opensource-roblox
An opensource project where changes connect to a game

**This game can be copied at <https://www.roblox.com/games/16715461770/OpenSource-Project> (click the three dots, then click Edit)**

## Instructions
Copy the game, make sure loadstring is enabled in the **ServerScriptService** (Explorer) and HTTP Requests are on in the **Game Settings** (>Security>Enable Http Requests).

Clone this repo and change the Repo Variable in the only Script in the ServerScriptService to your repo.

Create a release, and all servers will be shutdown to update. *Hint: All servers check in a 20 second interval for new releases*

## WARNING
All files in the fileindex.json file will be **executed in the order they are inputed**. They will **not be saved as scripts, rather directly executed in the ServerScriptService**.
