# Deploy to HEROKU

**<u>Important Note:</u>**
1. Add all of your private files here: `config.env`, `token.pickle`, `rcl.conf`, `accounts.zip` etc...

**<u>Mandatory Veriables in Config:</u>**

- `UPSTREAM_REPO`: Your github repository link, if your repo is private add `https://<username>:<password>@github.com/<your_username>/<repository_name>
` format. `Str`.
  - **NOTE**: Don't forget to remove '<' and '>' . 
- `UPSTREAM_BRANCH`: Upstream branch for update. Default is `upstream`. `Str`

- `BOT_TOKEN`: The Switch Bot Token that you got from [**Click Here**](https://graph.org/BOT-TOKEN-04-11). `Str`
- `OWNER_ID`: The Switch User ID (not username) of the Owner of the bot [**Click Here**](https://graph.org/OWNER-ID-04-11-2). `Int`
- `BASE_URL`: Add a valid `BASE URL` to use torrent selection. Copy it from your heroku app. Right click on `OPEN APP` and copy link address. Format of URL should be `https://APPNAME-IDENTIFIER.herokuapp.com/`, where `APPNAME` is the name of your heroku app and IDENTIFIER is an unic number. Example: `https://JetApp1-mjw69x6ex696.herokuapp.com/`. `Str`
- `TORRENT_TIMEOUT`: Timeout of dead torrents downloading with qBittorrent and Aria2c in seconds. `Int`

---
### For farther assistance visit my support group: [**@JetMirror**](https://telegram.me/JetMirror).
---

## Deploy using CLI

- Deployment instructions uploaded [**HERE**](https://gist.github.com/Hrishi2861/13454290bcd2ee01159579b304286bad)
- Carefully copy-paste every CMD one by one. If you miss maybe your BOT will not run.

- Format of [**@Z_Mirror**](https://t.me/Z_Mirror)
