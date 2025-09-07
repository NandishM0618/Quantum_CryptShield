# Quantum-CryptShield 🔐

Quantum-CryptShield is a **quantum-inspired, privacy-preserving data sharing system** designed for **IoT networks**. It combines modern encryption techniques, quantum-randomness-based entropy, and post-quantum cryptography (Kyber) to secure data transmission over lightweight protocols like MQTT. It also integrates a quantum-inspired ML model to detect and prevent cyberattacks such as Replay, MITM, and DoS.

![quant-project](https://github.com/user-attachments/assets/a7f609d3-5511-4adc-a008-1efbec9587a1)


---

## 🔧 Features

- **Quantum-Inspired Encryption**

  - AES-256-CBC encryption using quantum-generated randomness (QRNG).
  - Post-quantum key exchange using Kyber (ML-KEM-768).

- **IoT Integration**

  - Simulated MQTT-based IoT devices securely publish and receive encrypted data.
  - Replay protection using nonces and timestamps.

- **Cyberattack Detection**
  - Quantum-inspired machine learning model (QML) trained to detect replay, MITM, and DoS attacks.
  - Real-time attack logging and mitigation.

---

## 🚀 Getting Started

### Prerequisites

- Node.js >= 18
- Python >= 3.8 (for ML model)
- MQTT broker (e.g., Mosquitto or EMQX)

---

### 🛠 Installation

1. **Clone the Repository**

```bash
git clone https://github.com/NandishM0618/Quantum_CryptShield.git
cd Quantum-CryptShield
```

2. **Install Node.js Dependencies**

```bash
npm install
```

3. **Start the MQTT Broker (e.g., Mosquitto)**

```bash
mosquitto
```

4. **Start Backend Server**

```bash
node server.js
```

5. **Run IoT Device Simulation**

```bash
node iot_device.js
```

6. **Train & Run QML Model**

```bash
pip install -r requirements.txt
python train_model.py
python serve_model.py
```
