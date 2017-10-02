# node-bot-translator
This library retrieve a system to localize string that you have to share with the users of your bots.

##Implementing the system
Firstly, let's import and configure the package.
```javascript

const BotTranslator = require('bot-translator');

const translator = new BotTranslator({
  source: "utils/string.json", //
	storage: "mongodb" // Optional, standard use mongoose, so let be sure that you have mongodb installed before.
});
```
##string.json structure
