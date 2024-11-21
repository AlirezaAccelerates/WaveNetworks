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
Original paper: [WaveNet: A Generative Model for Raw Audio](https://arxiv.org/abs/1609.03499) \
Key Features: Causal convolutions, dilated kernels for long-term dependencies. 
#### WaveFlow
Overview: A flow-based model for fast and efficient audio generation. \
Original paper: [WaveFlow: A Compact Flow-based Model for Raw Audio](https://arxiv.org/abs/1912.01219) \
Key Features: Continuous normalizing flows, parallel synthesis. 
#### WaveGlow
Overview: A flow-based model combining the benefits of WaveNet and Glow. \
Original paper: WaveGlow: [A Flow-based Generative Network for Speech Synthesis](https://arxiv.org/abs/1811.00002) \
Key Features: Generative model with flow-based invertibility. 


## ✅ TODO



## 🤝 Contributing  

Contributions to this repository are welcome and greatly appreciated! Whether you're fixing bugs, adding new features, or improving documentation, your help is valuable. Here's how you can get started:

### How to Contribute  
1. **Fork the Repository**:  
   - Click the "Fork" button at the top right of this page to create a copy of this repository under your GitHub account.  

2. **Clone Your Fork**:  
   - Clone the forked repository to your local machine:  
        ```bash  
        git clone https://github.com/AlirezaAccelerates/WaveNetworks
        cd WaveNetworks
        ```

3. **Create a Branch**:  
   - Create a new branch for your feature or bug fix:  
     ```bash
     git checkout -b feature-name
     ```

4. **Make Changes**:  
   - Implement your changes locally and test thoroughly.

5. **Commit Your Changes**:  
   - Add your changes to the staging area and commit them with a descriptive message:  
     ```bash
     git add .
     git commit -m "Add a descriptive commit message here"
     ```

6. **Push Your Branch**:  
   - Push your changes to your forked repository:  
     ```bash
     git push origin feature-name
     ```

7. **Open a Pull Request (PR)**:  
   - Navigate to the original repository and click on "Compare & pull request."  
   - Fill out the PR template and submit your request.
