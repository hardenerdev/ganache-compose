# ganache-compose

docker compose based [ganache](https://github.com/trufflesuite/ganache) blockchain

## configure ganache

Edit env file after creating it:

```bash
cp .environment .env
```

## deploy ganache

```bash
git clone git@github.com:hardenerdev/ganache-compose.git
cd ganache-compose
docker compose up -d
```
