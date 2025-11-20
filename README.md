# DSE 425

**Topic:** Learning Implicit 3D Shape Representations for Surface Reconstruction
**Course:** *Robotic Perception*, IISER Bhopal

## Authors

- Sanad Shaha
- Om Govind Jha
- Sattwik Kumar Sahu
- Mohammad Saifullah Khan
- Chinamaya Bikram Pattnaik

---

## Papers Implemented

- DeepSDF
- Neural Kernel Surface Reconstruciton
- Convolutional Occupancy Networks
- SIREN

## Usage (Evaluation)

### DeepSDF

1. Pull the [docker image](https://hub.docker.com/repository/docker/sattwik21/dse425-3drep/general) and start the container
  ```bash
  docker pull sattwik21/dse425-3drep
  docker run -it --env="DISPLAY=:1" --net host --ipc host --runtime nvidia --gpus all --name dse425 sattwik21/dse425-3drep
  ```
2. Go to the DeepSDF folder directory
  ```bash
  cd ~/projects/deepsdf/DeepSDF
  ```
3. Create the virtual environment and install all dependencies
  ```bash
  uv sync
  uv
  ```
