# 🚀 Generative AI Internship Tasks — Prodigy Infotech

This repository contains my work for the **Generative AI Internship** at *Prodigy Infotech*.
I explored **text generation**, **image generation**, **Markov Chain-based text generation**, and **neural style transfer** using Python, Google Colab, and pre-trained models.

---

## 📌 Task 1: Text Generation using GPT-2

In this task, I explored **GPT-2**, a transformer model developed by OpenAI, to generate human-like text from a given prompt using the `transformers` library.

* **💬 Prompt Example:**
  `Once upon a time, there was a girl named Shreya...`

* **✨ AI Response Example:**
  `She was beautiful. She had a beautiful face. She was part of a beautiful family...`

* **🧠 What I Learned:**

  * Basics of GPT-2 and text generation
  * Using Hugging Face pipelines
  * Running AI models on Google Colab

* **📁 Files:**

  * `task1_gpt2_text_generation.ipynb` — Colab notebook for Task 1

---

## 📌 Task 2: Image Generation using Stable Diffusion

In this task, I used **Stable Diffusion** to generate images from text prompts using Hugging Face's `diffusers` library.

* **💬 Prompt Example:**
  `A futuristic city with flying cars`

* **🧠 What I Learned:**

  * How image generation models like Stable Diffusion work
  * Creating images from text prompts
  * Running models with GPU in Google Colab

* **📁 Files:**

  * `task2_image_generation.ipynb` — Colab notebook for Task 2
  * Generated image: `task2_image_futuristic_city_flying_cars.png`

---

## 📌 Task 3: Text Generation using Markov Chains

In this task, I implemented **Markov Chains** for simple text generation using probabilistic models built from input text.

* **💬 Input Example:**
  `Engines roar. Wheels spin. Speed thrills. Cars chase dreams.`

* **✨ AI Response Example:**
  `Wheels spin. Speed thrills. Cars chase dreams. Engines roar.`

* **🧠 What I Learned:**

  * How Markov Chains model text sequences
  * Writing Python code for Markov Chain text generation

* **📁 Files:**

  * `task3_markov_text_generation.ipynb` — Notebook for Task 3

---

## 📌 Task 5: Neural Style Transfer

In this task, I applied **Neural Style Transfer** to combine the content of one image with the artistic style of another.

* **🎨 Content Image:** *ghibli*

* **🌿 Style Image:** *nature*

* **🧠 What I Learned:**

  * How neural style transfer models work
  * Using pre-trained TensorFlow Hub models
  * Applying artistic styles using AI

* **📁 Files:**

  * `task5_neural_style_transfer.ipynb` — Notebook for Task 5
  * Generated image: `stylized_output.png`

---

## 🌟 Tools & Libraries Used

* Python
* Google Colab / Jupyter Notebook
* Hugging Face (transformers, diffusers)
* TensorFlow Hub
* Stable Diffusion, GPT-2
* GitHub for version control

---

## 💡 How to Run

✅ Open the `.ipynb` files in **Google Colab** or **Jupyter Notebook**
✅ Run the cells step-by-step
✅ For Task 2: Set runtime to **GPU** in Colab (*Runtime > Change runtime type > GPU*)
✅ Modify prompts or code to experiment further
