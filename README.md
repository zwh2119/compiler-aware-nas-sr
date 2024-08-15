# Towards Real-Time Video Super-Resolution on Edge Devices with Neural Architecture Search

## How to start

### Dependencies

```bash
conda create -n nas python=3.8
conda activate nas
conda install -y pytorch==1.9.1 torchvision==0.10.1 cudatoolkit=10.2 tensorboard h5py scikit-image -c pytorch
```

### Inference
```bash
python search.py
```