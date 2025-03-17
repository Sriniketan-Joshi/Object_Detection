# Object Detection models

## Grounded Segmentation with Grounding DINO and SAM

This repository provides code for performing grounded segmentation using two powerful models: Grounding DINO and Segment Anything Model (SAM).

**Overview**

This project demonstrates how to combine the strengths of Grounding DINO for object detection with textual prompts and SAM for precise segmentation of detected objects.

* **Grounding DINO:** Used to detect objects in an image based on text prompts.
* **Segment Anything Model (SAM):** Used to generate high-quality segmentation masks for the objects detected by Grounding DINO.

**Colab Notebooks**

This repository contains the following Jupyter notebooks:

* **`Grounding_DINO.ipynb`**: This notebook focuses on using the Grounding DINO model for object detection based on textual prompts. It includes steps for:
    * Installing necessary libraries.
    * Loading the Grounding DINO model.
    * Loading an input image.
    * Defining text prompts for object detection.
    * Running inference with Grounding DINO.
    * Visualizing the detected bounding boxes.
* **`Grounding_SAM.ipynb`**: This notebook builds upon the object detection capabilities of Grounding DINO by integrating SAM for segmentation. It includes steps for:
    * Installing necessary libraries.
    * Loading the SAM model.
    * Loading an input image.
    * Providing bounding box manually in the image.
    * Using the bounding boxes as input to SAM to generate segmentation masks.
    * Visualizing the original image with the generated segmentation masks overlaid.

**Getting Started**

1.  **Runtime Environment:** Ensure you have a suitable runtime environment in Colab (GPU recommended for faster inference). You can change the runtime type under `Runtime > Change runtime type`.
2.  **Install Dependencies:** The notebooks contain code to install the necessary Python libraries. Run these cells.
3.  **Follow the Instructions:** Each notebook will guide you through the process of loading models, inputting images, and running inference.
4.  **Experiment with Prompts:** Try different text prompts in the `Grounding_DINO.ipynb` or `Grounding_SAM.ipynb` notebook to detect and segment various objects in the images.
5.  **Input Images:** You can upload your own images to test the models.

**Prerequisites**

* Basic understanding of Python.
* Familiarity with Jupyter notebook enironment.
* Knowledge of object detection and image segmentation concepts can be helpful.

**Usage**

These notebooks can be used for:

* Experimenting with grounded object detection and segmentation.
* Understanding how to integrate Grounding DINO and SAM.
* Prototyping applications that require segmentation based on textual descriptions.

**Potential Extensions**

* Implement a user interface for easier interaction.
* Process videos instead of single images.
* Explore different configurations and parameters of Grounding DINO and SAM.
* Integrate with other downstream tasks.

**Acknowledgements**

* This work is based on the research and implementations of Grounding DINO and the Segment Anything Model (SAM). We acknowledge the authors and contributors of these models.

---
