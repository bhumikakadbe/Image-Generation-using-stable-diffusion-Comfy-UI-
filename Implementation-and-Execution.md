
# Implementation & Execution Guide

---
## 1. Implementation Steps

This section outlines how to set up and run Stable Diffusion with ComfyUI on Windows.

**Step 1:** Download ComfyUI

1. Open a browser (Chrome, Edge, etc.).


2. Go to GitHub and search for ComfyUI or directly visit:
https://github.com/comfyanonymous/ComfyUI


3. Scroll down and find the Download for Windows section.


4. Click the download link to get the ComfyUI Windows version.



**Step 2:** Extract ComfyUI Files

1. After downloading, locate the compressed file (.zip or .rar) in your system.


2. Extract the file using WinRAR or Windows File Explorer.


3. Open the extracted ComfyUI_Windows folder.



**Step 3:** Download and Add the Stable Diffusion Model

1. Open a browser and visit the Hugging Face platform:
https://huggingface.co


2. Search for Stable Diffusion v1.5 model.


3. Download the v1-5-pruned-emaonly-fp16.safetensors file.


4. Once downloaded, navigate to:

ComfyUI_Windows/comfyui/models/checkpoints


5. Paste the downloaded .safetensors model file inside the checkpoints folder.




---

## 2. Execution Steps

**Step 1:** Run ComfyUI

1. Go back to the ComfyUI_Windows folder.


2. To run the UI on your system:

**If using GPU:**

python main.py --gpu

**If using CPU:**

python main.py --cpu



3. Wait for the server to start.



**Step 2:** Open ComfyUI in Browser

1. Once the server is running, open a web browser.


2. Go to:

http://127.0.0.1:8188


3. This will open the ComfyUI interface.




---

## 3. Generating Images with ComfyUI

1. In the ComfyUI interface, enter a text prompt.


2. Adjust parameters like resolution, sampling steps, and guidance scale.


3. Click Generate to create an image.


4. The generated images will be saved in the output folder of ComfyUI.




---

## 4. Sample Output
 **Prompt** :-An ancient floating library suspended in the sky, surrounded by glowing magical runes,cascading waterfalls flowing from its edges 
  hovering books flipping through their pages mid-air,agolden sunset,8K resolution,fantasy art style

  

---
![ComfyUI_00010_](https://github.com/user-attachments/assets/4d9c7c71-e75a-4268-bfd4-02852c928b26)

## 5. Troubleshooting

### Issue: ComfyUI Not Launching

Ensure Python and all dependencies are installed.

Run:

pip install -r requirements.txt


### Issue: Model Not Detected

Confirm the safetensors file is in the correct folder:

ComfyUI_Windows/comfyui/models/checkpoints

Restart ComfyUI after adding the model.



---

This repository ensures users can install, execute, and generate images using ComfyUI and Stable Diffusion.

💬 Feel free to reach out for collaborations, discussions, or queries related to this project.

📌 Name : Bhumika Kadbe

📌 Email: bhumikakadbe@gmail.com
