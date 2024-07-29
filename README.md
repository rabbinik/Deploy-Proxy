# Swisstronik Tesnet Techinal Task 6 (Deploy Proxy)

link : [Click!](https://www.swisstronik.com/testnet2/dashboard)

Feel free donate to my EVM address

EVM :

```bash
0x7086918cD79Db480cEEF0eB473C4290936EA40ec
```


## Steps

### 1. Clone Repository

```bash
git clone https://github.com/rabbinik/Deploy-Proxy.git
```

```bash
cd swisstronik-deploy-proxy
```

### 2. Install Dependency

```bash
npm install
```

### 3. Set .env File

create .env file in root project

```bash
touch .env
```

add this to your .env file

```bash
PRIVATE_KEY="your private key"
```

### 4. Compile Smart Contract

```bash
npm run compile
```

### 5. Deploy Smart Contract

```bash
npm run deploy
```

### 6. Initialize Owner

```bash
npm run initialize
```

### 7. Add Issuer

```bash
npm run add-issuers
```

### 8. Get Issuers list

```bash
npm run list-issuers
```

### 9. Upgrade Smart Contract

```bash
npm run upgrade
```

### 10. Uploud ke github

```bash
git init
git add .
git remote set-url origin https://github.com/rabbinik/Deploy-Proxy.git
git push -u origin main
```
### 11. Finsihed

- Open the deployed-adddress.ts file (location in utils folder)
- Select SWTRProxy
- Copy the address and paste the address into testnet dashboard(Point1)
- Open address-with-explorer.txt file (location in utils folder)
- Copy the address explorer and paste the address into testnet dashboard(Point2)
- Open tx-hash.txt file (location in utils folder)
- Copy the transaction hash link and paste the address into testnet dashboard(Point3)
- No need push to github

by :
github : [rabbinik](https://github.com/rabbinik)
