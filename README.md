🖼️ Image Captioner with Gradio (VGG-based)

This project is an **image captioning application** that uses a **VGG-based convolutional neural network** for image feature extraction and generates human-like captions for images. The application is wrapped in an intuitive **Gradio** interface, allowing users to easily upload an image and receive a descriptive caption.

🚀 Features

- Upload an image via a simple interface
- Automatically generates a natural-language caption
- Powered by a VGG network for visual feature extraction
- Clean and minimal Gradio front-end

🧠 How It Works

1. **Image Feature Extraction**: The uploaded image is passed through a **pre-trained VGG model** (like VGG16 or VGG19) to extract rich visual features.
2. **Caption Generation**: The extracted features are passed to a decoder model (like an LSTM or Transformer) that generates a caption based on the visual context.
3. **Gradio Interface**: Allows easy interaction with the model via browser.
