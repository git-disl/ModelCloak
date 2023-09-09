
## description

This is the code for IEEE ICDM 2023 paper: Model Cloaking against Gradient Leakage.

## For Gradient leakage resilient federated learning

- Go to DP_code folder

- First install the conda environment with environment.yml.

- Then run create\_FLdistribution.sh to create a client distribution first (each client has two shards). The distribution file xxx_1000_clients.pkl would appear in the client folder and you may run the rest.

- This code includes both the participation-level Fed-SDP (FedSDP.py), and instance-level Fed-CDP with certified parameter search (FedCDP\_certified.py). You may adjust the few lines within the local training for accuracy oriented differential privacy parameter search. The privacy accounting approach is also provided for ε privacy spending in Fed-CDP.

## For leakage attacks

- Go to gradient_leakage/ folder for gradient leakage attacks on MNIST, Fashion-MNIST, CIFAR10 and LFW (both type 1 leakage and type 2 leakage).







