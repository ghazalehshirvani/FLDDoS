# Federated Learning for DDoS Attack Detection

🔒 **Federated Learning**
<div style="text-align: justify;">
Welcome to the Federated Learning for DDoS Attack Detection repository! This project utilizes federated learning approaches to detect DDoS (Distributed Denial of Service) attacks with higher accuracy compared to other similar approaches. The implementation includes FedAVG and FedAVGM as consensus algorithms, with results showcased in the provided code.
</div>

## Introduction to Federated Learning
<div style="text-align: justify;">
Federated Learning is a machine learning approach that enables training models across decentralized devices or servers holding local data samples, without exchanging them. Instead of sending raw data to a central server, each device computes an update to the global model using its local data and shares only the model parameters. This privacy-preserving technique is particularly useful in scenarios where data privacy is a concern, such as healthcare, finance, and cybersecurity.
</div>

## Collaborators

This project was a collaboration between:
- [Ghazaleh Shirvani](https://github.com/ghazalehshirvani)
- [Saeid Shirazi](https://github.com/saeidshirazi)

## Project Overview
<div style="text-align: justify;">
The project is developed in Python and utilizes PyTorch, Pandas, NumPy, and Seaborn libraries. The code is organized into several Jupyter Notebooks:
</div>

1. **Data Preprocessing**: Preprocesses the data and plots the final dataset distributions. Screenshots of the final dataset distributions can be found in the `FinalDataset_Distribution_ScreenShot` folder.
2. **Methodology**:
    - `FedAVG.ipynb`: Implements the FedAVG algorithm for federated learning.
    - `FedAVGM.ipynb`: Implements the FedAVGM algorithm for federated learning.

## Experimental Environment

The code has been tested on the following experimental environment:
- **CPU**: Intel Core i9 12900K (24 virtual CPU)
- **RAM**: 60GB
- **GPU**: Nvidia 3090 Ti
- **HDD**: 80GB OS disk
- **OS**: Windows 10, 64-bit

## Requirements

Ensure you have the following modules installed:
- **CUDA Toolkit**: 11.2
- **CuDNN**: 8.1.0
- **PyTorch**: 2.0
- **Python**: 3.9

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/ghazalehshirvani/FLDDoS
    ```

2. Install the required modules:
    ```bash
    pip install torch torchvision pandas numpy seaborn
    ```

3. Open and run the Jupyter Notebooks to explore the data preprocessing and methodology implementation.

## Additional Notes

- The trained model weights are saved in the `global.pt` file.

Feel free to explore the code, experiment with different parameters, and contribute to further enhancing the DDoS attack detection using federated learning!
