# Simple Blockchain Simulation ⛓️

This project is a **basic blockchain simulation** implemented in Python. It mimics core blockchain features such as **linked blocks, hashing, proof-of-work, transaction management, and chain validation**.

## 🚀 Features
✅ Block structure with index, timestamp, transactions, previous hash, and current hash  
✅ SHA-256 hashing for block integrity  
✅ Chain validation to detect tampering  
✅ Proof-of-Work for computational difficulty  
✅ Dynamic transaction handling before mining  
✅ Docker support for easy deployment  

---

## 🛠️ Installation

### Prerequisites
- Python 3.9+ installed
- Docker (optional for containerized deployment)

## Docker Deployment
- docker build -t blockchain-simulation .
- docker run --name blockchain-sim blockchain-simulation
