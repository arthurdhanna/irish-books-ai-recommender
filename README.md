# 📚 Irish Books – AI-Powered Book Recommendation Wizard

This is a prototype of an AI-driven book recommendation tool developed for **Irish Books**, an independent bookshop in Ranelagh, Dublin. It provides customers with a personalised recommendation experience based on their reading preferences, mood, and interests, all while showcasing how generative AI could be integrated into a retail environment responsibly.

---

## 🎯 Project Goals

- **Enhance customer experience** through interactive book discovery
- **Explore the potential of AI** in small retail environments
- **Preserve trust and human engagement** by providing explainable, thoughtful recommendations

---

## 🚀 How It Works

The tool runs entirely in the browser and guides users through four quick steps:

1. **Input** the last book they enjoyed
2. **Choose genre and sub-genres**
3. **Select their mood**
4. **Pick a recommendation style** (e.g., Popular, Hidden Gem)

It then presents a **sample recommendation**, designed to mimic the kind of output a real AI model would generate.

---

## 🤖 GPT-4 Integration (Commented for Reference)

This project includes a **non-active code block** (commented in JavaScript) that demonstrates how to integrate OpenAI’s GPT-4 via API to generate real-time recommendations.

**📎 You’ll find this in `getRecommendation()` inside the HTML file.**

To enable:
- Replace `"YOUR_OPENAI_API_KEY"` with your actual API key
- Uncomment the relevant code
- Use a secure backend or proxy to protect the key in production

> ⚠️ The GPT logic is *not currently enabled* to avoid exposing sensitive API keys or causing unexpected live behavior.

---

## 🛠 Technologies Used

- **HTML5, CSS3 & JavaScript (Vanilla)**
- Responsive and mobile-friendly design
- Styled with embedded custom CSS (no external frameworks)
- Designed for rapid prototyping and easy extension

---


## 🧩 Future Enhancements

- Enable secure GPT integration with server-side proxy
- Link to real inventory for in-stock title suggestions
- Enable account-based personalization and saved preferences
- Add accessibility features to comply with EU Accessibility Act

---

## 👤 Author

**Arthur Hanna**  
AI Strategy & Innovation | Fenergo  
📧 arthur.hanna@fenergo.com

---

## 📄 License

This repository is intended for **educational and prototype use only**.  
Do not use GPT APIs in production without implementing proper data protection and compliance.

---

