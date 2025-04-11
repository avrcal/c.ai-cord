# c.ai-cord
Chat with Character ai with your friends but on discord! 


# what does this bot do?
- you can chat with c.ai character by simple command !


# what type of bots does it support?
 - it support 2 types original bot and self bot
 - (the self bot if you want to prank people from payphone discord bot from userphone or yaggdrasil bot for userphone)

# whats the commands?
- there is only two command
- 1 *ai (character_id)
- 2 *stopai

# how to get character id? 
## you can get it by visiting c.ai website and go to the character you want and go to the character link and you can find it after the "chat/" thing



# how to get character token?


## About tokens and how to get them
>
> ⚠️ WARNING, DO NOT SHARE THESE TOKENS WITH ANYONE! Anyone with your tokens has full access to your account!

This library uses two types of tokens: a common `token` and `web_next_auth`. The first one is required for almost all methods here and the second one only and only for `upload_avatar()` method (may change in the future).

### Instructions for getting a `token`

1. Open the Character.AI website in your browser
2. Open the `developer tools` (`F12`, `Ctrl+Shift+I`, or `Cmd+J`)
3. Go to the `Nerwork` tab
4. Interact with website in some way, for example, go to your profile and look for `Authorization` in the request header
5. Copy the value after `Token`

> For example, token in `https://plus.character.ai/chat/user/public/following/` request headers:
> ![img](https://github.com/Xtr4F/PyCharacterAI/blob/main/assets/token.png)

### Instructions for getting a `web_next_auth` token

1. Open the Character.AI website in your browser
2. Open the `developer tools` (`F12`, `Ctrl+Shift+I`, or `Cmd+J`)
3. Go to the `Storage` section and click on `Cookies`
4. Look for the `web-next-auth` key
5. Copy its value

> ![img](https://github.com/Xtr4F/PyCharacterAI/blob/main/assets/web_next_auth.png)

---

