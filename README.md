# 🚀 NOMA Communication over Rayleigh Fading Channel

## 📖 Overview

This repository contains **MATLAB simulations** of a **Non-Orthogonal Multiple Access (NOMA)** system under **Rayleigh fading channel conditions**.  
The project evaluates **Bit Error Rate (BER)**, **Outage Probability**, and **Rate / Capacity (SINR)** across varying transmit power levels.  

NOMA is a key enabler for **5G and beyond**, allowing multiple users to share the same resources with power-domain multiplexing.

---

## 📌 Table of Contents
- [✨ Features](#-features)
- [🛰️ System Model](#️-system-model)
- [📊 Simulated Metrics](#-simulated-metrics)
- [⚙️ How to Run](#️-how-to-run)
- [📂 Directory Structure](#-directory-structure)
- [🛠️ Dependencies](#️-dependencies)
- [📈 Results & Plots](#-results--plots)
- [🔮 Future Work](#-future-work)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)

---

## ✨ Features

✔️ NOMA simulation under **Rayleigh fading**  
✔️ Performance vs **Transmit Power (SNR)**  
✔️ Metrics analyzed:  
   - 📉 Bit Error Rate (BER)  
   - 📉 Outage Probability  
   - 📈 Rate / Capacity / SINR  
✔️ MATLAB `.fig` results included  
✔️ Modular scripts for plotting  

---

## 🛰️ System Model

- **Channel**: Rayleigh fading model  
- **Users**: Multiple users with different **power allocation factors**  
- **Encoding**: Superposition coding  
- **Decoding**: Successive Interference Cancellation (SIC)  
- **Variable Parameters**: Transmit power, SNR range, channel gains  

---

## 📊 Simulated Metrics

| Metric              | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| **BER**             | Probability of decoding error per transmitted bit                          |
| **Outage Probability** | Chance that SINR/Rate < threshold                                         |
| **Rate / Capacity** | Achievable throughput under fading & interference                          |

---

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Akash-R-04/Noma-communication.git
   cd Noma-communication
   
2. Open MATLAB and run the scripts:
BER_vs_Tx_power
Outage_Prob_vs_Tx_power
Rate_SINR_vs_Tx_power

3. Adjust parameters (SNR range, power allocation, users) inside the scripts.

🛠️ Dependencies
1. MATLAB R2020a or newer
2. (Optional) Signal Processing & Communications Toolbox

📈 Results & Plots
Below are sample outputs from the simulation:

📉 BER vs SNR Curve [![BER vs SNR Curve](https://github.com/Akash-R-04/Noma-communication/blob/main/ber%20vs%20transmit%20power.jpg)]()
📉 SNR vs Transmit power [![SNR vs Transmit power](https://github.com/Akash-R-04/Noma-communication/blob/main/br.jpg)]()
📈 Capacity vs SNR Curve [![Capacity vs SNR Curve](https://github.com/Akash-R-04/Noma-communication/blob/main/capacity.jpg)]()
📈 Outage Probability vs SNR Curve [![Outage Probability vs SNR Curve](https://github.com/Akash-R-04/Noma-communication/blob/main/outage%20probability.jpg)]()

🔮 Future Work
1. Multi-user (>2) NOMA scenarios
2. Imperfect CSI impact
3. Power allocation optimization
4. Comparison with OMA / OFDMA
5. Time-varying fading with mobility

🤝 Contributing
Contributions are welcome! 🎉
1. Fork this repo
2. Create a feature branch (git checkout -b feature-name)
3. Commit your changes (git commit -m 'Add feature')
4. Push to branch (git push origin feature-name)
5. Create a Pull Request
