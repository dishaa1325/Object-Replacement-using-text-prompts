# Object-Replacement-using-text-prompts
**Overview**

1. This project demonstrates an automated pipeline for object replacement in images using cutting-edge deep learning models.
2. The implementation integrates YOLOv8 for object detection, SAM (Segment Anything Model) for precise mask generation, and Stable Diffusion for inpainting and object replacement.

**Features**
1. Automatic Mask Generation: Generates masks for objects dynamically based on user-specified prompts, ensuring no manual masking is required.
2. Object Replacement: Replaces objects in an image as per the user's prompt, with seamless blending.
3. Background Replacement: Demonstrates the capability of replacing entire backgrounds in images using SAM + Stable Diffusion.
4. Interactive Gradio Interface: Allows users to upload images, specify objects to replace, and provide replacement prompts.

**Run the Pipeline:**

Colab Notebook: Load the provided Colab notebook, execute the cells in sequence, and view the outputs.
Gradio Interface: Run the Gradio-based interactive app to test the pipeline with custom images and prompts.
