# Quantum Chat

Quantum Chat is a secure messaging system that uses Quantum Key Distribution (QKD) for cryptographic key generation and RSA for key exchange. It comprises a NodeJS server, a Svelte client, and a QKD Python server for quantum key generation. [Report](https://github.com/CubeStar1/QuantumChat/blob/main/static/report/QKD_EL_Phase_3.pdf)

<img src="https://github.com/CubeStar1/QuantumChat/blob/main/static/quantum-chat-architecture.jpg" alt="Quantum Chat Architecture" style="border-radius: 10px;" />

## Key Features

- Server-side component in TypeScript with WebSocket communication
- Client-side component in Svelte using IndexedDB for local storage
- Quantum Key Distribution for generating secure symmetric keys
- Hybrid encryption system combining symmetric and asymmetric encryption
- AES-CTR algorithm for message encryption and decryption

## Setup and Installation

### Prerequisites

- Node.js and npm (for TypeScript server and Svelte client)
- Python 3.7+ and pip (for QKD server)
- PowerShell (for Windows users)

### 1. Clone the Repository

### 2. QKD Server


#### Using `start.py`

1. **Activate the Virtual Environment:**
   Ensure your virtual environment is activated:

2. **Run the Script:**
   Execute the `start.py` script to generate and run the PowerShell script that starts the APIs:

#### Manually

1. **Activate the Virtual Environment:**


2. **Start Each API:**

### 3. NodeJS Backend

### 4. Svelte Frontend



## Running the Application

1. Ensure the QKD server is running on port 8000
2. Start the NodeJS backend (it will run on port 3000)
3. Launch the Svelte frontend (typically on port 5000 or 5173)
4. Access the application through the URL provided by the Svelte frontend

