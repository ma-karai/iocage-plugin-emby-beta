# Emby Server for FreeNAS 11.3 ONLY

Requires FreeNAS 11.3

This Installation method will create a Jail that is fully configurable via the FreeNAS GUI

From the FreeNas CLI (shell)

LATEST BETA (27)

    cd /tmp
    wget https://raw.githubusercontent.com/ma-karai/iocage-plugin-emby-beta/master/emby-server-beta.json
    iocage fetch -P emby-server-beta.json

