# Lichess Statfish Bot
Lichess deployment for [Statfish UCI module](https://github.com/loicmarie/statfish).
StatFish is a UCI module wrapping StockFish, that will play first moves according to human opening usage statistics, allowing players to train against the most frequent openings. 

## Framework
You can find the framework used to deploy the bot [in this repo](https://github.com/careless25/lichess-bot/).

## Deployment
- Install virtualenv: `pip install virtualenv`
- Setup virtualenv:
```
virtualenv .venv -p python3 #if this fails you probably need to add Python3 to your PATH
source .venv/bin/activate
pip install -r requirements.txt
```
- Copy `config.yml.default` to `config.yml`
- Replace the token with the one you generated on Lichess.org.
