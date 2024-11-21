# Wave Networks Repository  
A collection of cutting-edge generative models, including WaveNet, WaveFlow, and WaveGlow, implemented in Keras.

---

## 📖 Table of Contents  
- [Overview](#overview)  
- [Features](#features)  
- [Getting Started](#getting-started)  
  - [Installation](#installation)  
  - [Running with Docker](#running-with-docker)  
- [Models](#models)  
  - [WaveNet](#wavenet)  
  - [WaveFlow](#waveflow)  
  - [WaveGlow](#waveglow)  
- [TODO](#todo)  
- [Contributing](#contributing)  
- [License](#license)  

---

## 📚 Overview  
This repository is a hub for research and experimentation with generative networks used in signal generation and processing. These models leverage different techniques, like autoregressive and flow-based, to generate high-fidelity signals.

---

## ✨ Features  
- Implementations of popular wave networks: **WaveNet**, **WaveFlow**, and **WaveGlow**.  
- Easy-to-use scripts for training, inference, and evaluation.  
- Pre-configured Docker environment for seamless setup.  
- Dependencies managed with `requirements.txt`.  

---

## 🚀 Getting Started  

### Prerequisites  
Ensure you have the following installed:  
- Python 10.0+  
- Docker  

### Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/AlirezaAccelerates/WaveNetworks
   cd WaveNetworks
   ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt  
    ```

### Running with Docker
1. Build the Docker image:
    ```bash 
    docker build -t WaveNetworks .  
    ```
2. Run the container:
    ```bash
    docker run -it --rm -p 8888:8888 WaveNetworks 
    ```

## 📊 Models
#### WaveNet
Overview: A deep autoregressive model for audio generation. \
Original paper: 
Key Features: Causal convolutions, dilated kernels for long-term dependencies. \
#### WaveFlow
Overview: A flow-based model for fast and efficient audio generation. \
Original paper: 
Key Features: Continuous normalizing flows, parallel synthesis. \
#### WaveGlow
Overview: A flow-based model combining the benefits of WaveNet and Glow. \
Original paper: WaveGlow: [A Flow-based Generative Network for Speech Synthesis](https://arxiv.org/abs/1811.00002) \
Key Features: Generative model with flow-based invertibility. \