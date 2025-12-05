## How to make your own

### 🚀 Deploy on Heroku

[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

Then go to the [variables tab](/README.md#environment-variables) for info on setting up environment variables.

### 🖥 Host on VPS / Locally

```sh
git clone https://github.com/DeekshithSH/TG-FileStreamBot
cd TG-FileStreamBot
python3 -m venv ./venv
. ./venv/bin/activate
pip3 install -r requirements.txt
python3 -m WebStreamer
```

To stop the bot, press <kbd>CTRL</kbd>+<kbd>C</kbd>

To keep it running 24/7 on VPS:

```sh
sudo apt install tmux -y
tmux
python3 -m WebStreamer
```

You can now close the terminal and the bot will keep running.


## Environment Variables

[Click here for Environment Variables](/README.md#environment-variables)

If you're on Heroku, add these as Config Vars.  
If hosting locally, create a `.env` file in the root directory and add them there.