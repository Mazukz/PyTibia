# 📝 Description

> Fastest Tibia PixelBot developed in python to get unlocked fps.

This bot memorizes works locating image around the screen and applies cache to avoid image redetection and thus avoid excessive cpu/gpu usage.

This bot is all based on matrix calculation, also applies parallelism and also pre-processing, as it is the only way to have maximum performance.

The main goal is to work with "microseconds" using complex algorithms, calculations, etc.

This bot also uses data structure, arrays, path finding(djkistra), among other important things to have smart decisions and gameplay.

I created this bot to learn python, to stream on twitch, to make friends, to apply my knowledgments in deep learning, path finding, matrix, etc.

I'm not going to sell subscription to this bot, but it will work on "global" and you can use it, it's at your own risk.

This BOT ins't ready yet, this bot still under construction.

Be free to use any function to create your custom bot or wait for the release of v0.

# 🗺️ V0 Features Status

- ActionBar:
  - Counting slots :heavy_check_mark:
  - Getting cooldowns for knight:
    - attack :heavy_check_mark:
    - exori :heavy_check_mark:
    - exori mas :heavy_check_mark:
    - exori gran :heavy_check_mark:
- BattleList:
  - [Getting monsters](battleList/docs/README.md) :heavy_check_mark:
  - [Checking if monster is being attacked](battleList/docs/README.md) :heavy_check_mark:
  - Is attacking any creature :heavy_check_mark:
- Cavebot:
  - Attacking closest creature :heavy_check_mark:
  - Ignoring non target monsters :heavy_check_mark:
  - Resume coordinate :heavy_check_mark:
  - Retarget to another creature when current target is non attackable :heavy_check_mark:
- Chat:
  - Check if Server Log is selected :heavy_check_mark:
  - Talk to NPC's to trade :heavy_check_mark:
- Equipment:
  - Count cap :heavy_check_mark:
  - Auto ring :heavy_check_mark:
- Loot:
  - Get dead monsters by player
    - Parse server logs message to get loot notification :heavy_check_mark:
    - Get dead monster by target :heavy_check_mark:
    - Get dead monster by exori :heavy_check_mark:
  - Collect loot :heavy_check_mark:
    - When hunting, go to dead monster to collect :heavy_check_mark:
    - Detect container full :heavy_check_mark:
- Healing:
  - Spell :heavy_check_mark:
  - Potion :heavy_check_mark:
- HUD:
  - Getting coordinates(playable area) :heavy_check_mark:
  - Getting Monsters :heavy_check_mark:
- Radar:
  - Floor level :heavy_check_mark:
  - Tracking coordinates :heavy_check_mark:
- Refill:
  - Deposit items in depot :heavy_check_mark:
  - Detect trade container :heavy_check_mark:
  - Scroll until icon is detected :heavy_check_mark:
  - Buy necessary quantity of icon :heavy_check_mark:
- Spell:
  - Apply exori when there are a certain number of monsters around :heavy_check_mark:
- Status:
  - Getting Life :heavy_check_mark:
  - Getting Mana :heavy_check_mark:

# ⚽ Goals

- Detect every necessary information in the client in (milli/macro/nano)seconds
- Walk through keyboard
- Control every pixel of the mouse to make human movements
- Use convolutionals neural networks to detect relevant stuffs like blockable objects, dropped loots, etc
- Use recurrent neural networks to use natural language processing to chat with others players
- Crack kernel or put tibia working in a sub system to avoid BE detections
- Make party gameplay
- Make a guild gameplay, start a war and dominate a tibia server
- Raise money and send $ to help my Venezuelan friends who are experiencing economic difficulties

# 🧰 Installation

## Prerequisites

- Python >=3.9.12
- Poetry >=1.2.0

Install packages before continue

```bash
poetry install
```

# ⌨ Development

## ⚙ Running the app

```bash
poetry run python main.py

# to test last experiments with mess code
poetry run python test.py
```

## 🧪 Running tests

```bash
# unit tests
poetry run python -m pytest
```

# ✅ TODO

- Add api docs
- Add mypy
- Add e2e tests into the tibia client
- Add pytest-cov
- Add python typings

# 👷 Authors

- [**lucasmonstro**](http://github.com/lucasmonstro)([**linkedin**](https://www.linkedin.com/in/lucasmonstro/)) - Owner & Developer
- [**augustocrmattos**](http://github.com/augustocrmattos)([**linkedin**](https://www.linkedin.com/in/augustocrmattos/)) - Developer
- [**GuizinhoYT**](http://github.com/GuizinhoYT)([**linkedin**](https://www.linkedin.com/in/guilherme-gra%C3%A7a-3953231a2/)) - Tester
- [**lelec0**](https://github.com/lelec0)([**linkedin**](https://www.linkedin.com/in/max-miranda/)) - Developer

See also the list of [contributors](../../graphs/contributors) who participated
in this project.

If you want to become a contributor, send a message to my [**linkedin**](https://www.linkedin.com/in/lucasmonstro/).

# ❤️ Development inspiration

A special thanks to [**Murilo Chianfa**](https://github.com/MuriloChianfa), the owner of [**TibiaAuto12**](https://github.com/MuriloChianfa/TibiaAuto12). I started this bot especially to overcome [**TibiaAuto12**](https://github.com/MuriloChianfa/TibiaAuto12) slowdowns.

You can check the bot development at [https://twitch.tv/lucasmonstrocs](https://twitch.tv/lucasmonstrocs).

# 📝 License

Copyright © 2021 [**lucasmonstro**](https://github.com/lucasmonstro)  
This project is [MIT](https://opensource.org/licenses/MIT) licensed
