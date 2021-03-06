# PoB Parsing Bot for Discord
*Written in Python 3.6*

### Do not forget to re-do your config.py every time you pull. Breaking changes may happen at this stage.
### Used Libraries
- refer to the [requirements.txt](/requirements.txt)

### Utilized libraries & Inspiration:
- [discord.py](https://github.com/Rapptz/discord.py)
- [PoBPreviewBott](https://github.com/aggixx/PoBPreviewBot)
- [LiftDiscord Bot](https://github.com/andreandersen/LiftDiscord/)
### Important
- Setting your own keyword has been disabled via the config. You need to change it in
### Finished
- Support for having active channels where the bot fetches all pastebin links and tries to past
- Support for having passive channels where the bot only triggers when using the command
- Parsing most of the information from the XML into classes to facilitate extensive custom output
- Various config options in `config.py`
- Secondary Defenses
- Primary defenses need to hit Thresholds to be displayed

### Future Work
- Refine Offense output
    - Poison/Ignite and Dots in general are crude
    - Maybe:
        - Balls
        - Arrows
- Start/Stop script: https://wolfpaulus.com/technology/pythonlauncher/
- Add support for Keystones
    - Number of totems
- Support for Auras from Items (check if they're active)
- Add support for "Notable" Uniques that are displayed in the extended version
- !pob `manually input build name here` <pob link>
- Split auras into def and supporting auras


### How To Run
- Copy and rename `config.example.py`
  ```bash
  cp config.example.py config.py
  ```
- Edit the new `config.py`
    - replace token
    - add channels the bots should react to and define keyword(s)
- Run `discord_pob.py`
- Bot logs into `discord_pob.log`

If you need more thorough insturctions see the wiki entry: [Usage](https://github.com/FWidm/discord-pob/wiki/Usage)

### Usage
- Bot reacts to `!pob <pastebin (not raw!) link>` in all configured passive channels on the invited server or to pastebin links it can parse in active channels.

### Showcase
![](https://cdn.discordapp.com/attachments/418758449954947076/423174211373236224/unknown.png)

