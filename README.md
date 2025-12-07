# amapoolminer

**`amapoolminer`** is the GPU miner for the [Amadeus (AMA)](https://ama.one) cryptocurrency, designed specifically for mining on the [AMA Mining Pool](https://ama-pool.com).

It supports both **NVIDIA** (via CUDA) and **AMD** (via OpenCL) graphics cards.

---

## 🔗 Links

- **Pool**: [https://ama-pool.com](https://ama-pool.com)  
- **Releases (Binaries)**: [https://github.com/amapool/amapoolminer/releases](https://github.com/amapool/amapoolminer/releases)

---

## 🚀 Quick Start

1. Download the latest release for your operating system from the [Releases](https://github.com/amapool/amapoolminer/releases) page.
2. Extract the archive (if applicable).
3. Run the miner with your wallet address and worker name:

### Linux
```bash
./amapoolminer -host pool.ama-pool.com:4444 -wallet YOUR_WALLET_ADDRESS -worker YOUR_WORKER_NAME
```

### Windows
```cmd
amapoolminer.exe -host pool.ama-pool.com:4444 -wallet YOUR_WALLET_ADDRESS -worker YOUR_WORKER_NAME
```

> **Note**: Make sure you have up-to-date GPU drivers installed for optimal performance.


## 🛰️ HiveOS Integration

You can easily deploy `amapoolminer` on HiveOS using a flight sheet:

1. Download the file **`hiveos-flightsheet-template.json`** from the [Releases](https://github.com/amapool/amapoolminer/releases) page.
2. In the HiveOS web interface, go to the **"Flight Sheets"** section.
3. Click **"Add New Flight Sheet"** → **"Import from File"**, and select the downloaded `hiveos-flightsheet-template.json`.
4. Click **"Add wallet"**, then in the popup window enter your **Amadeus (AMA) wallet address** in the **Address** field and click **"Create"**.
5. Finalize the setup by clicking **"Create Flight Sheet"**.
6. Apply the newly created flight sheet to your worker(s).

---

## 📦 Supported Platforms

- **Linux** (x86\_64)
- **Windows** (x64)

---

## ❓ Support

If you have questions:
- Check the [FAQ](https://ama-pool.com) on the pool website
- Open an issue in the [Issues](https://github.com/amapool/amapoolminer/issues) section if you encounter a bug

---

## 📜 License

All rights reserved by [ama-pool.com](https://ama-pool.com).  
The software is provided **"as is"**, without any warranties, expressed or implied.

---

Thank you for contributing to the **Amadeus (AMA)** network! 💎🛠️
