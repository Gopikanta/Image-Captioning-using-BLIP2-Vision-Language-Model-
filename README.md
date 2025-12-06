# Image-Captioning-using-BLIP2-Vision-Language-Model-
 This project demonstrates an image captioning system built using BLIP-2, a powerful Vision–Language Model. The application takes an input image, processes it using a pretrained BLIP-2 FLAN-T5-XL model, and generates a natural, human-like description. 

Image Captioning using BLIP-2 (Vision–Language Model)

This project demonstrates how to generate natural language descriptions from images using BLIP-2, a state-of-the-art Vision–Language Model (VLM).
The system accepts an input image and produces a meaningful caption using Salesforce’s BLIP-2 Flan-T5-XL model.
A user-friendly interface is provided using Gradio.

**Features**

📷 Upload any image

🧠 Uses BLIP-2 (Vision + Language Model)

✨ Generates natural, human-like captions

⚡ Fast inference with GPU support

🌐 Simple and interactive Gradio interface

**Model Used**

This project uses a single VLM model:

🔹 BLIP-2 (Salesforce/blip2-flan-t5-xl)

BLIP-2 internally contains:

* Vision Encoder (ViT-L/14) → Understands image

* Q-Former → Connects vision to language

* Flan-T5-XL → Generates the text caption

**How It Works**

User uploads an image through Gradio

-- BLIP-2 processor converts the image into tensors

-- BLIP-2 model extracts visual features

-- Q-Former connects vision → text

-- Flan-T5-XL generates a caption

-- Caption is displayed to the user

**Example Output**

Input: Image of a dog running
Output:
"A dog running through a grassy field."

**Future Improvements**

-- Add voice output (text-to-speech)

-- Add image-question answering

-- Upload multiple images at once

-- Deploy to HuggingFace Spaces
