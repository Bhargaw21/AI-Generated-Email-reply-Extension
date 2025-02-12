🌟 AI-Generated-Email-Reply-Extension

🎯 Overview

The AI-Generated-Email-Reply-Extension is a powerful Chrome browser extension that helps users quickly generate AI-driven email replies directly in Gmail. Users can choose from various tones (e.g., formal, casual, empathetic, professional), and the AI will generate tailored, tone-specific replies. The extension seamlessly integrates with Gmail, adding an "AI Reply" button beside the "Send" button.

✨ Features

🎭 Tone Selection: Choose from multiple tones like formal, casual, empathetic, and professional.
🤖 AI-Generated Replies: Automatically generate contextually relevant replies based on the selected tone.
📩 Seamless Integration: Adds an "AI Reply" button beside the "Send" button in Gmail.
🖥️ User-Friendly Interface: Minimal and intuitive design for a smooth user experience.

⚙️ How It Works

1.Install the extension in Google Chrome.
2.Open Gmail and compose a new email or reply to an existing one.
3.Select the desired tone from a drop-down menu.
4.Click the "AI Reply" button.
5.The AI will generate a reply based on the selected tone and the email content.
6.Edit or send the generated reply as needed.

🛠️ Development

🛑 Technologies Used

JavaScript: For browser actions and Gmail DOM manipulation.
HTML/CSS: For UI and button styling.
AI API Integration: Utilizes an AI API (e.g., OpenAI or Google AI) to generate email replies.
Frontend: React
Backend: Spring Boot

📝 Sample manifest.json
{
  "manifest_version": 3,
  "name": "AI-Generated-Email-Reply-Extension",
  "version": "1.0",
  "description": "Generate AI-based email replies with different tones in Gmail.",
  "permissions": ["activeTab", "scripting"],
  "content_scripts": [
    {
      "matches": ["https://mail.google.com/*"],
      "js": ["content.js"]
    }
  ],
  "action": {
    "default_popup": "popup.html",
    "default_icon": "icon.png"
  }
}

🚧 Limitations

* Requires internet connectivity to generate AI responses.
* Manual edits may be necessary for certain replies.

🚀 Future Enhancements

* Add more tone options (e.g., humorous, apologetic).
* Allow user customization of tone settings.
* Support for other email platforms (e.g., Outlook, Yahoo Mail).

🤝 Contributing

Contributions are welcome! To contribute:
Fork the repository.
Create a new branch for your feature/fix.
Submit a pull request.

📜 License
This project is licensed under the MIT License.

📧 Contact

For issues or suggestions, contact the developer:
Email: BhargawKumarSingh@gmail.com
GitHub: Bhargaw21
