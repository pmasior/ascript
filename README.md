# ascript

Definitions for Azure containers

## Run lab envioronment

```bash
git clone https://github.com/pmasior/ascript.git
cd ascript/lab
touch .env
docker compose up
docker compose exec speechcli bash
spx recognize --key none --host ws://speechtotext:5000/ --file __filename__
```
