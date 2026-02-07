# Mintlify Landing Page (HTML & CSS)

A responsive landing page inspired by the **Mintlify** website, built using **pure HTML and CSS only**.  
This project focuses on clean layout design, semantic HTML structure, and modern CSS styling — without using JavaScript.

---

## 🌐 Live Demo
_(Optional)_  
If deployed, add your live site link here:

👉 https://mintlify-landing-page-gold.vercel.app/




🛠️ Tech Stack
HTML5: Semantic structure.

CSS3:

Flexbox & Grid: Primary layout engines.

Custom Properties (Variables): For consistent color branding.

Keyframe Animations: For the live status pulse effect.

Google Fonts: "Inter" font family for that modern SaaS look.

Font Awesome: For scalable vector icons.

📁 Project Structure
```
Plaintext
├── assets/
│   ├── newimg/           # Product images, badges, and logos
│   └── mintlify-logo.svg # Brand assets
├── index.html            # Main site structure
├── style.css             # Modular stylesheet
└── README.md             # Project documentation
```
🎨 Key CSS Highlights
Pixel-Perfect Centering
The project uses a dedicated container class to ensure content is tucked in from the edges, matching professional SaaS layouts:

CSS
.footer-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 40px;
}
The Status Pulse Animation
To create the "Live" feel in the footer:

CSS
@keyframes pulse {
    0% { transform: scale(1); opacity: 0.8; }
    100% { transform: scale(2.5); opacity: 0; }
}
⚙️ Installation & Usage
Clone the repository:

Bash
git clone https://github.com/yourusername/mintlify-clone.git
Open the project: Navigate to the project folder and open index.html in your preferred browser. Recommended: Use the Live Server extension in VS Code for real-time updates.

📝 License
This project is for educational purposes as a UI/UX layout study. Original design rights belong to Mintlify.