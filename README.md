# billiards

## files
- main.py : flask stuff
- bot.py : bot stuff
- config.ini : config stuff
- database.py : sqlite wrapper
- break_info.py : class to store break info
- users.db : users' best breaks
- breaks.db : all 7+ breaks

## pip packages
pip install -r requirements (set up later)
- discord.py
- flask
- flask_cors

## config.ini
[discord]
server = {server ID}
channel = {channel ID}

[secrets]
token = {app token}
appID = {app ID}

## testing setup
python3 -m venv env
source env/bin/activate
pip install discord flask flask_cors

flask --app main run