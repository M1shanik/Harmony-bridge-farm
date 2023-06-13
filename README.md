# Harmony-bridge-farm
This script bridge ~0.0004 BNB (random values) from BSC network to Harmony chain using Layerzero bridge. It costs you less then 0.1$ in total. Best way to farm layerzero activity so far.

## Prerequisites

- Top your account with BNB in BSC network
- Add private keys to data.txt (one line - one key)
- You might change min/max delay between accounts in harmony-bridge-bsc.py

## Installation

Run commands like this:

```
apt install python3-pip, git
git clone https://github.com/Kizliak/Harmony-bridge-farm
cd Harmony-bridge-farm
pip install -r requirements.txt
```

Add private keys:

```
nano private_key.txt
```

Run script
```
python3 harmony-bridge-bsc.py
```
