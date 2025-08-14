# 1. Create local folder and enter it
mkdir Crypto_Roadmap && cd Crypto_Roadmap

# 2. Create the Markdown file
cat <<EOT >> Crypto_Roadmap.md
# Crypto Management & Collateral Roadmap
**Designed by Chadwick Alan Chauncey**

## Step 1: Set Up Robinhood & Deposit Crypto
1. Create & verify your Robinhood account (KYC)
2. Link your bank account for USD deposits
3. Deposit or buy crypto (BTC, ETH, other coins you own)

## Step 2: Enable & Fund Robinhood Crypto Wallet
1. Enable sending/receiving for all supported coins
2. Transfer crypto from external wallets (optional)
3. Confirm on-chain transfer completion

## Step 3: Using Crypto as Collateral
1. Check margin or loan eligibility
2. Only deposited crypto can serve as collateral
3. Monitor borrowing limits to avoid liquidation
4. Schedule repayments carefully

## Step 4: Monitor & Manage Transactions
1. Track all deposits and withdrawals
2. Monitor open positions and collateral regularly
3. Only send crypto to wallets you control

## Step 5: Security & Compliance
1. Enable two-factor authentication (2FA)
2. Use strong passwords and keep backup keys offline
3. Only manage crypto you legally own

## Step 6: Advanced Portfolio & Collateral Strategy
1. Diversify holdings (BTC, ETH, other coins)
2. Optimize collateral usage
3. Periodically rebalance your portfolio
4. Use leverage cautiously
EOT

# 3. Optional: Copy the visual diagram
# cp /path/to/Crypto_Roadmap.png .

# 4. Initialize git
git init
git branch -M main
git remote add origin https://github.com/your-username/your-repo.git

# 5. Stage and commit files
git add Crypto_Roadmap.md Crypto_Roadmap.png
git commit -m "Add Chadwick Alan Chauncey crypto roadmap"

# 6. Push to GitHub
git push -u origin main