# Twitch TTS - Language Autodetect

This tool will trigger on Twitch chat messages, detecting their written language before reading it out loud (TTS - Tex to speech)

## Installation

You will need python and pip

### Run this to install required libraries
```bash
pip install -r requirements.txt
```

### Then do

* Copy the file `config.ini.example` to `config.ini`
* Edit `config.ini` to your Twitch username and your Twitch OAuth token
 
 Get you OAuth token here: https://twitchapps.com/tmi/

## Usage

```bash
python main.py
```

Or turn this project into an single file executable by using pyinstaller

```bash
pip install pyinstaller
pyinstaller --onefile --paths path\to\venv\Lib\site-packages main.py
```

Alternatively, I will do this for you and you can get the compiled file under the [releases](https://github.com/lacksfish/twitch-tts-language-autodetect/releases).

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[Chicken Dance License v0.2](https://github.com/supertunaman/cdl/blob/master/COPYING)