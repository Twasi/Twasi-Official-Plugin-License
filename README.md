
*This license is an alpha version and not completed yet.*
#

### Twasi Official Plugin License v0.1-Alpha (TOPL v0.1-Alpha)

1.  **Definitions:**
    
	- By “TwasiBot” we mean the official hosted instance of “Twasi Core” ([https://github.com/Twasi/twasi-core](https://github.com/Twasi/twasi-core)). Self-hosted instances are not meant.
    
	- By "Twitch" or "TwitchTV" we mean the live-stream video platform "Twitch", which can be found at [https://twitch.tv/](https://twitch.tv/).
    
	- By “Twasi Development Portal” we mean our official platform which is designed to help developers to develop plugins for “Twasi-Core” ([https://dev.twasi.net/](https://dev.twasi.net/)).
    
	- By “plugin” we mean an extension of Twasi-Core, no matter if it is officially provided by us or was coded by a third party developer.
    
	- By “official plugin” or “official plugin dependency” we mean plugins provided by us to guarantee various functions  for the TwasiBot or third party APIs provided by us that allow developers to extend the functionality of their plugin as long as this plugin contains the latest version of this license. These plugins and plugin dependencies can be found at the Twasi Development Portal or in our GitHub repositories ([https://github.com/Twasi](https://github.com/Twasi)).
    

2.  **Intentions of the license:**
    

	- This license is intended to be used in official Twasi-Core plugins, official Twasi-Core plugin dependencies or plugins created using the Twasi Development Portal.
    
	- The license must be included in every plugin you want to run on TwasiBot.
    

3. **Permissions:**
    

	- While Twasi-Core (MIT-License) is allowed to be used in any way this plugin or dependency of Twasi-Core is not. You are not allowed to use it in a productive, self-hosted environment __except__ this environment is only for personal usage and not for a public productive usage.
    
	- You are allowed to run this plugin on a local Twasi-Core instance for testing purposes, development and debugging. Productive usage on a local Twasi-Core instance is allowed, as long as it is only used for personal purposes and doesn't compete with us.
    
	- You are allowed to use the official plugin dependencies in your plugin to provide more functionality as long as all terms of the latest version of this license (TOPL) are met.
    

4.  **Conditions for the inclusion of the plugin in the live operation of the TwasiBot:**
    

	- The plugin must have a public repository on GitHub ([https://github.com](https://github.com)) containing
    

		-  the latest version of this license and no other licenses
    
		- a readme.md file that describes the plugin’s functionalities
	    - a “src” folder followed by your Twasi Development Portal initials (called “base package”), which you set up at the first use of the Twasi Development Portal.
    
		- a resources folder containing the plugin.yml (file that contains settings of your plugin) and all language files in the "/translations" subfolder
    
		- the plugin’s source code
	- All database collections, all used permission keys and all translation message keys must start with the developers base package.
	- The plugin must extend the TwasiBots functionalities and needs to be useful for users in any way. It is allowed to process personal data of the bot's users if possible - as long as . It is not allowed to share this data with the responsible developer or third parties of any kind. The privacy of all users needs to be guaranteed by __every__ developer.
	- The plugin must contain a description that explains it's functionalities and how it can be used.
