# Text-to-Image-Generation-Using-Python-AI
Generate high-quality realistic images from text prompts — or transform input images — using the Realistic Vision v6.0 (HyperVAE) Stable Diffusion model. No API keys. Fully offline. Built with Python, Tkinter GUI, and Flask Web UI.

🚀 Features

	•	✅ Text-to-Image (txt2img)
 
	•	✅ Powered by Stable Diffusion
 
	•	✅ Transparent PNG output (512x512)
 
	•	✅ Works Offline (No internet required after setup)
 
	•	✅ Choose between:
	•	🖥️ Tkinter GUI (Desktop App)
	•	🌐 Flask Web UI (Browser)
 
	•	✅ Save, Preview, and Copy Output Paths
 
	•	✅ Model runs on CPU or GPU (CUDA if available)
 
	•	✅ Built-in Dark Mode

Download Model from : https://civitai.com/models/4201/realistic-vision-v60

Rename it : realisticVisionV60B1_v51HyperVAE.safetensors

Paste it in the same folder where app.py is present





📦 Installation

1. Clone the Repository

   
    git clone https://github.com/your-username/text-to-image-generator.git
cd text-to-image-generator

2. Create & Activate a Virtual Environment

   
      python3 -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

3. Install Requirements
Install each dependency individually (for macOS compatibility):


    pip install torch torchvision
pip install diffusers transformers safetensors pillow flask





🧪 Example Prompts

Prompt: A beautiful sunset over a calm lake, vibrant colors, ultra realistic

🌸 Aesthetic / Positive Vibes Prompts


✨ General Beauty & Nature

	1.	A beautiful sunset over a calm lake, vibrant colors, ultra realistic
 
	2.	A peaceful forest path with soft sunlight filtering through trees, 8k, cinematic lighting
 
	3.	A cozy cabin in snowy mountains during golden hour, photorealistic
 
	4.	A sunflower field under a clear blue sky, high detail, macro photography
 
	5.	A magical waterfall surrounded by glowing flowers and soft mist, fantasy realism
 

⸻

🌟 People (Positive Representation)

	6.	A smiling young woman in traditional Indian attire, soft lighting, DSLR style
 
	7.	A joyful child playing with soap bubbles in a park, golden hour, candid shot
 
	8.	An old man with a gentle smile reading a book under a tree, peaceful atmosphere
 

⸻

🎨 Artistic / Creative

	9.	A dreamlike floating island in the sky, colorful clouds, surreal art
 
	10.	A fantasy city built on giant trees, glowing lights, magical realism
 
	11.	A futuristic peaceful city with flying cars and greenery, sunny day, clean art style
 
	12.	A serene zen garden with koi pond, bamboo trees, and a small bridge, ultra detailed
 

⸻

🌈 Wholesome Moments

	13.	A happy dog running through a meadow of flowers, bright daylight
 
	14.	A family having a picnic under a large oak tree, laughter, warmth, photorealistic
 
	15.	A couple watching stars together with a telescope on a hill, night sky full of stars
 

Negative Prompt: (deformed, low quality, blurry, duplicate, poorly drawn hands, bad anatomy, ugly, text, cartoon)



📁 Project Structure
📦 Text-to-Image-Generator


─ app.py                                                 # Flask Web UI

─ gui.py                                                # Desktop GUI using Tkinter

─ requirements.txt

─ output/                                                # Generated images saved here
  
─ static
   └── frames                                             # UI Assets
   
─ realisticVisionV60B1_v51HyperVAE.safetensors            # Model file

⚠️ Disclaimer
This project uses an unfiltered AI model. Generated content depends entirely on prompts provided by the user. Use responsibly and for educational or personal purposes only.


💻 Running the Application (For Macbook Pro)

  cd ~/Documents/"Text to Image Generation Using Python AI"

  source venv/bin/activate

  python app.py


💾 Hardware Requirements

                          
RAM: 8GB ( Minimum  )                16 GB or more ( Recommended )

Disk Space: 10 GB ( Minimum  )    15–20 GB  ( Recommended )

GPU: Optional           CUDA-enabled GPU (for faster generation)  ( Recommended )

CPU: Any modern CPU ( Minimum  )       Apple M-series or Intel i7/i9 preferred for speed ( Recommended )



 🤔How It Uses AI and ML
 

🔍 1. Machine Learning Model
	•	The project uses pre-trained deep learning models, such as Stable Diffusion and Realistic Vision v6.0, which are created using large datasets of image-text pairs.
	•	These models are trained using machine learning algorithms (e.g., transformers, variational autoencoders) that learn patterns between text and image features.
 

🧠 2. Artificial Intelligence
	•	The AI system understands your text input (prompt) and uses the trained model to generate new, realistic images that match your description.
	•	This is a form of Generative AI—where the model creates new content rather than just classifying or predicting.
 

⚙️ 3. Frameworks That Power ML in This Project
	•	torch (PyTorch): Deep learning framework.
	•	diffusers: From Hugging Face, used for implementing diffusion models like Stable Diffusion.
	•	transformers: Used to tokenize and interpret text prompts.
	•	realesrgan, gfpgan: Optional upscaling or face enhancement models that are also based on ML.










