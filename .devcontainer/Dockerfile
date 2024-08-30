# Use the TensorFlow notebook as the base image from quay.io
FROM quay.io/jupyter/tensorflow-notebook:cuda-latest

# Install PyTorch with CUDA support
RUN pip install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu118

# Install any additional dependencies
# RUN pip install <other-dependencies>

# Set the working directory
WORKDIR /home/jovyan/work

# Expose necessary ports (if any)
EXPOSE 8888