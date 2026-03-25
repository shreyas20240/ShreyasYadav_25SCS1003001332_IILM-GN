# ShreyasYadav_25SCS1003001332_IILM-GN
AI Image Caption Generator

This project is an AI-powered Image Caption Generator that automatically generates natural language descriptions for images. It combines computer vision and natural language processing to understand visual content and convert it into meaningful text.

The system uses a CNN-based model to extract features from the input image, which are then passed to a GPT-2 model implemented in Google Colab for caption generation. GPT-2 helps produce fluent and human-like captions without the need for training a model from scratch.

A simple and interactive Gradio interface is used, allowing users to upload an image and instantly receive a generated caption through a web browser.

🚀 Features
	•	Upload image and generate captions instantly
	•	Uses pre-trained CNN + GPT-2 model
	•	Runs on Google Colab (no heavy local setup required)
	•	Simple Gradio web interface
	•	Easy to extend (multilingual, styles, batch processing)

🛠️ Tech Stack
	•	Python
	•	CNN (for image feature extraction)
	•	GPT-2 (for caption generation)
	•	Gradio (for UI)
	•	Google Colab

📌 Future Improvements
	•	Multiple caption suggestions
	•	Style-based captions (funny, formal, social media)
	•	Multilingual support
	•	Batch image processing
