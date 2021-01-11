# BlackUserbot
Userbot telegram che contiene molti plug in da friday 
# Installa Git First.
git clone https://github.com/starkGang/FridayUserbot
# Apri Git Cloned File 
cd FridayUserbot
 # Config Virtual Env
virtualenv -p / usr / bin / python3 venv
. ./venv/bin/activate
 # Installa tutti i requisiti
pip install -r requisiti.txt
# Crea local_config.py con le variabili come indicato di seguito 
# Avvia Bot 
python3 -m fridaybot





VARS OBBLIGATORIE
[+] Only two of the environment variables are mandatory.

[+] This is because of telethon.errors.rpc_error_list.ApiIdPublishedFloodError

    [-] APP_ID:   You can get this value from https://my.telegram.org
    [-] API_HASH :   You can get this value from https://my.telegram.org
    
[+] The fridaybot will not work without setting the mandatory vars.
