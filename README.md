# 📸 Cleanliness Score Camera Module

The **Cleanliness Score Camera Module** is a cutting-edge TinyML-driven solution designed to revolutionize cleanliness monitoring in the hospitality industry. This project combines AI, edge devices, and innovative design to deliver real-time cleanliness scores for hotel rooms and short-term rentals.

## 🚀 Features
- **AI-Powered Cleanliness Scoring**: Leverages a CNN model to evaluate room states as clean, slightly untidy, or dirty.
- **Customizable Hardware**: Xiao ESP32S3 Sense microcontroller with a 160° camera, housed in a durable, laser-cut enclosure.
- **Sustainability Integration**: Supports guest accountability with potential integrations for rewards programs like Marriott Rewards.
- **Scalable Deployment**: Built for real-time monitoring, API integration, and smart property management systems.

## 📊 Dataset & Model
### Dataset:
- **Custom**: 30 images per category from various room states.
- **Online**: 250 images per category from Kaggle and scraped Airbnb data.
- **Generated**: 30 AI-generated images per category using DALL-E.
- **Total**: 930 images across 3 categories (Clean, Slightly Untidy, Dirty).

### Model:
- **Architecture**: CNN with 96x96 RGB input, 3 convolutional layers, ReLU activations, and dropout for overfitting prevention.
- **Accuracy**:
  - Test Accuracy (3-Class): **81.48%**
  - Quantized Model Accuracy: **76.52%**
- **Optimization**: Quantized to 8-bit for edge deployment (reduced size from 10.1 MB to 685 KB).

## 🛠️ Hardware & Deployment
- **Microcontroller**: Xiao ESP32S3 Sense with WiFi, Bluetooth, and TinyML capabilities.
- **Tools**: Google Colab for model development and ArduinoIDE for deployment.
- **Integration**:
  - Dual wall mounts for 3D image mapping.
  - Plans for an iOS app and API/SDK compatibility.

## 🎥 Demo
👉 [Watch the Demo Video](2e422f98aea44da5a9d92be4966d9ae4.mov)

## 🛑 Challenges & Future Work
### Challenges:
- Fine-tuning the model for edge devices.
- Bias in Airbnb datasets towards clean rooms.
- Integration of sensors in a compact, production-ready device.

### Future Work:
- Expand dataset with diverse real-world images.
- Integrate advanced sensing like LiDAR for 3D modeling.
- Develop partnerships for pilot testing with major hospitality chains.
- Expand applications to rideshare vehicles, warehouses, and supermarkets.

## 🌟 Vision
The Cleanliness Score Camera Module redefines cleanliness monitoring, improving operational efficiency, enhancing guest satisfaction, and promoting sustainability. With further development, this technology will set new standards across property management and beyond.

---

💡 **Want to contribute or learn more?** Check out the code and documentation! Let’s build smarter, cleaner spaces together. 🌍
