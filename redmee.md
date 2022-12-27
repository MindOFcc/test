version 1.0.1

#BY_Jean-Luc_Nakajew___Jonns_

Vorraussetzung:
    
    - 2GB Speicher
    - Docker und Docker-compose
        - Wenn nicht installiert schaue unten letzte zeile(Installation-Von-Docker-und-docker-compose)
    - WSL
        - Wenn nicht schaue Microsoft webseite(WLS aktivieren oder installieren)
    - python 2.4 oder höher
   
Installation:
    
    1. Docker install
        - Linux
            - console starten
                - apt-get update && apt-get upgrade -y
                - apt-get install docker -y && apt-get docker-compose -y
                - service --status-all
                - service docker start
        - Windows
            - docker downloaden
    2. docker-compose
        - Linux
            - docker-compose up
        - Windows
            - cmd
                - docker-compose up