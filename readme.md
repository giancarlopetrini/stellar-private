# stellar-private

### Quick way to run local standalone stellar networks for development purposes

## Use a persistent setup
1. `cd persistent`
2. `docker-compose up -d`
3. `docker exec persistent_stellar_1 stellar-core --c /upgrades?mode=set&[upgradetime=1970-01-01T00:00:00Z&basereserve=0&basefee=0`