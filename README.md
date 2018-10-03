![image.png](http://i.imgur.com/eQeaMUk.png)

# DiscordZero

DiscordZero is a Python Script that allows you to get Discord SMS notifications on your phone - Free of charge, anywhere in the world!

# Getting started
#### Installation
```git clone https://github.com/0xCoto/DiscordZero```

#### Usage

```
cd DiscordZero
python DiscordZero.py
```


# Mechanism
DiscordZero uses the [`Discord.py`](https://github.com/Rapptz/discord.py) library to hook on to account notifications. Once a message has been received, an SMS is sent through the Hologram.io [Web API](https://hologram.io/docs/reference/cloud/http/#/reference/hologram-cloud/sms/send-sms-to-a-device) which is received in less than 10 seconds after being sent.

# Credits
DiscordZero was created by [@0xCoto](https://github.com/0xCoto) and [@samdenty99](https://github.com/samdenty99).
