# RSDT Mining Pool

Professional mining pool server for RSDT Resistance Blockchain

## 🚀 Quick Start

```bash
# Install dependencies
pip3 install aiohttp requests

# Configure pool
cp pool_config.json.example pool_config.json
# Edit pool_config.json with your settings

# Start pool
python3 rsdt_mining_pool.py
```

## ⚙️ Configuration

Edit `pool_config.json`:

```json
{
    "daemon_url": "http://127.0.0.1:18081",
    "pool_fee": 1.0,
    "min_payout": 0.1,
    "database": "rsdt_pool.db",
    "pool_address": "your-pool-wallet-address",
    "pool_port": 3333,
    "api_port": 8080
}
```

## 📊 Features

- **Stratum Protocol**: Standard mining protocol support
- **Real-time Stats**: Live mining statistics
- **Database**: SQLite for persistent storage
- **API**: REST API for pool statistics
- **Multi-worker**: Support for multiple miners

## 🔗 Related Repositories

- [RSDT Blockchain](https://github.com/rsdt/rsdt-blockchain)
- [RSDT Miners](https://github.com/rsdt/rsdt-miners)
- [RSDT Website](https://github.com/rsdt/rsdt-website)

## 📄 License

BSD 3-Clause License
