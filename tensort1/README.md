# Tensor rt Practice

This is repocitory for learning and practising TensorRT

ResNET -> ONNX -> TENSORT 

Simple without measuring performance etc

Run the tensor rt container:

    docker run --gpus all -it --rm   --network host   -v $(pwd):/workspace   nvcr.io/nvidia/tensorrt:24.03-py3

Install:

    python -m pip install --upgrade pip

    pip install -r requirements.txt

Create a jypeter lab server inside the container: 

    jupyter lab --ip=0.0.0.0 --port=8888 --no-browser --allow-root

Open a jupyter and connect to the kernel specified in terminal.
