
---

# Hear-2-See

Hear-2-See is an innovative assistive technology project that bridges the gap between sight and sound, empowering the visually impaired to understand their surroundings like never before. This repository contains the source code for the Hear-2-See web application. 

## Overview

Hear-2-See employs image recognition technology and audio synthesis to create a seamless connection between what is seen and what is heard. It provides a real-time solution for transforming images into meaningful sounds, enabling users to comprehend their surroundings more effectively.

### Features

- **Image Capture**: Users can capture real-time photos using their device's camera. The captured images are processed and described in real-time.

- **Image Upload**: Users can upload images from their device's personal collection. The uploaded images are processed and described, providing valuable feedback.

- **Enhanced Descriptions**: The system uses various image recognition services, including Google Cloud Vision and Azure Computer Vision, to generate textual descriptions of the images. It then uses OpenAI's language model to enhance and consolidate these descriptions, creating concise, informative summaries.

- **Audio Feedback**: The enhanced descriptions are converted into speech using Google Text-to-Speech (gTTS) and played back to the user, making it a powerful tool for visually impaired individuals to understand their surroundings.

- **Contact**: Users can get in touch with the project team by sending emails directly from the web application.

## Getting Started

To run this application locally, you'll need to set up the required credentials and dependencies. Here are the steps to get started:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ShriramJana/Hear2See
   cd hear-2-see
   ```

2. **Install Dependencies**:
```bash
Make sure to install the following Python packages to run the application:

- Streamlit
- VertexAI
- OpenAI
- Google Cloud SDK
- Azure SDK
- gTTS (Google Text-to-Speech)
- PIL (Python Imaging Library)
- smtplib
- io
- streamlit_option_menu
   ```

3. **Configure API Keys and Credentials**:
   - You'll need API keys and credentials for services such as Google Cloud, Azure Cognitive Services, and OpenAI. Update the necessary credentials in the code.

4. **Run the Application**:
   ```bash
   streamlit run hear2see.py
   ```

The web application will be accessible in your browser.

## Contributing

We welcome contributions to this project. If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test them.
4. Submit a pull request with a clear description of your changes.

## Contact

If you have any questions or feedback, feel free to get in touch with us. You can contact us via email:

- Project Team Email: hear2see.recep@gmail.com

## License

This project is licensed under the [MIT License](LICENSE).

---
