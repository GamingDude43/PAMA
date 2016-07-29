<p align="center">
  <a href="https://hydrabolt.github.io/discord.js">
    <img alt="discord.js" src="http://hydrabolt.github.io/discord.js/res/logo.png" width="546">
  </a>
</p>
---

### Example: ping-pong
```js
var Discord = require("discord.js");

var mybot = new Discord.Client();

mybot.on("message", function(message) {
	if(message.content === "ping") {
		mybot.reply(message, "pong");
    }
});

mybot.loginWithToken("token");
// If you still need to login with email and password, use mybot.login("email", "password");
```
---

### Links
**[GitHub](https://github.com/GamingDude43/PAMA)**

---

### Contact

If you would like to contact me, you can create an issue on the GitHub repo, e-mail me via the one available on my NPM profile.
