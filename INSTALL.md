# INSTALL.md

## Pre-requisites

### Mandatory environment and containers tools

- **Python 3.8+**
- **Docker** 

###  Python dependencies

Install required modules :
```bash
pip install -r requirements.txt
```

---

## INSTALL

1. **Fork github repository** :
    ```bash
    git clone https://github.com/votre-utilisateur/meteo-data-hub.git
    cd meteo-data-hub
    ```
2. **Setup environment** :
    - Create configuration JSON files .
3. **Build micro-services** :
    - Lancez les conteneurs Docker pour les microservices :
      ```bash
      docker-compose up
      ```
