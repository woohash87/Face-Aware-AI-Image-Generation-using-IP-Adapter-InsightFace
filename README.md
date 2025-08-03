# Face-Aware-AI-Image-Generation-using-IP-Adapter-InsightFace
This project is a face-based AI image generation tool that creates personalized and highly realistic images using IP-Adapter models and face embeddings. By combining Stable Diffusion, InsightFace, and Hugging Face Transformers, users can generate images that preserve the identity of an uploaded face image.

**Features**
Upload a face image and get highly realistic generations
Control face structure, likeness strength, and prompt
Uses IP-Adapter FaceID and FaceID Plus models
Face detection using InsightFace
Simple Gradio interface for web-based interaction

**Technologies Used**
Python
Hugging Face Diffusers
IP-Adapter from Tencent AI Lab
InsightFace for face alignment
Gradio for interactive UI
Torch, ONNX, OpenCV
**Setup Instructions**
# Install dependencies
!pip install torch diffusers transformers insightface opencv-python gradio huggingface_hub accelerate safetensors onnxruntime

# IP-Adapter from source
!pip install git+https://github.com/tencent-ailab/IP-Adapter.git
 **Sample Usage (Gradio)**
 gr.Interface(fn=generate_image, inputs=[...], outputs="image").launch()
**Credits**
Inspired by Hugging Face + Tencent IP-Adapter + InsightFace.
Models from: HuggingFace Hub
IP Adapter: Tencent-AILab/IP-Adapter
**Note:**
This project is built for educational purposes and showcases face-aware image generation. It does not store or misuse any uploaded facial data.
