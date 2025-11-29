# hardhat.config.js
| Name             | Wert                                                       |
| ---------------- | ---------------------------------------------------------- |
| PRIVATE_KEY      | Dein Wallet Private Key                                    |
| BASE_RPC         | z. B. [https://mainnet.base.org](https://mainnet.base.org) |
| TREASURY         | Deine Treasury-Adresse                                     |
| BASESCAN_API_KEY | Optional, für Verification                                 |
# Repo klonen, falls noch nicht
git clone https://github.com/MarcMaverick/Toffix-.git
cd Toffix-

# Dependencies installieren
npm install

# Compile
npx hardhat compile

# Deployment auf Base (testweise, ggf. Testnet)
npx hardhat run scripts/deploy.js --network base
