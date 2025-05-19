# image-generator
 AI Image Generator (HTML, CSS, JavaScript)
A simple and elegant AI-powered Image Generator built with HTML, CSS, and JavaScript. Enter a prompt, click generate, and watch AI bring your imagination to life!

Powered by image generation APIs like OpenAI DALL·E or Stability AI.

🌟 Features
✨ Pure front-end implementation (HTML/CSS/JS)

📸 Generate images from text prompts

🔁 Multiple generations per prompt (configurable)

💾 Save/download generated images

🧼 Clean and responsive UI design

🚀 Live Demo
👉 View Live Project

Make sure you’ve configured API access correctly. Client-side access to secret keys is not recommended for production.

📁 Project Structure

image-generator/
├── index.html         # Main HTML file
├── style.css          # Styling
├── script.js          # Main JavaScript logic          
├── README.md          # Documentation

🛠️ Getting Started
1. Clone the repository
git clone https://github.com/yourusername/image-generator.git

2. Set up API Access
You will need an API key from:

OpenAI for DALL·E or Stability AI

⚠️ Never expose your API keys in client-side JavaScript!
Use a serverless proxy (e.g., via Cloudflare Workers, Vercel Functions, or Netlify Functions) to keep keys secure.

🧠 How It Works
User enters a prompt in a text field.

JavaScript sends the prompt to a backend or serverless function.

Backend fetches the generated image from the AI API.

Image is displayed in the browser with the option to download.

📸 Example Prompts
"a futuristic city underwater, digital art"

"a cat astronaut floating in space"

"a watercolor painting of a forest in autumn"
	

📦 Dependencies
HTML5 / CSS3 / Vanilla JS

AI Image Generation API (e.g., OpenAI or Stability AI)

🛡️ Security Note
This is a frontend-only demo. To keep your API keys secure in production:

Use a backend proxy or serverless function

Never expose OPENAI_API_KEY or STABILITY_API_KEY directly in script.js

🪪 License
This project is licensed under the MIT License.

🙏 Credits
OpenAI

Stability AI

Hugging Face diffusers

Contributors & the open-source community
