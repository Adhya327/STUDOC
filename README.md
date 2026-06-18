Readme · MDCopy<div align="center">
📚 Studoc — Academic Vault

Student Document Management & Intellectual Community Platform

Show Image
Show Image
Show Image
Show Image


Upload. Organize. Connect. — Everything a student needs, in one place.



</div>

📖 Table of Contents


About the Project
Key Features
Tech Stack
Getting Started
Project Structure
Contributing Guidelines
Future Phases
License



🌟 About the Project

Studoc is a web-based student productivity platform designed to solve two core problems every student faces: losing important documents and studying in isolation.

Studoc gives students a personal academic vault to store, organize, and access their documents anytime — and connects them to a community of driven peers for academic guidance, discussion, and collaboration.

🎯 Target Users

RoleDescriptionPlatform CapabilitiesStudentPrimary user of the platformUpload & manage documents, build a resume, post in the communityPeer LearnerCommunity participantAsk questions, share resources, reply to discussionsGuestVisitor exploring the platformBrowse community posts and platform features


✅ Key Features

🔐 Authentication


Email & password sign-in with role-based access.
Guest mode for exploring the platform without an account.


📂 Document Vault


Upload any file type — PDF, DOCX, PPTX, images, and more.
Drag & drop support for fast uploads.
Auto-categorization into Science, Math, Humanities, Engineering, and Other.
Search and filter documents by category.
Delete documents you no longer need.


📄 Resume Builder


Fill in personal details, education, skills, and projects.
Instantly generates a clean, styled resume preview.
Export-ready layout designed for academic and internship applications.


🌐 Student Community


Post thoughts, questions, and resources to a shared feed.
Tag posts by topic: Mathematics, Computer Science, Physics, Career Advice, Resources.
Like, reply to, and share any post.
Filter the feed by topic tag.
Live "students online" counter for a sense of active community.


🎨 UI & Experience


Dark scholarly theme — midnight navy with amber gold accents.
Smooth page transitions and micro-animations throughout.
Toast notifications for every user action.
Fully responsive — works on desktop, tablet, and mobile.



🛠️ Tech Stack

CategoryTechnologyPurposeStructureHTML5Page layout and contentStylingCSS3Theme, animations, responsive designLogicVanilla JavaScript (ES6+)Interactivity, DOM manipulation, stateFontsGoogle FontsPlayfair Display, DM Sans, JetBrains MonoIconsUnicode symbolsLightweight, dependency-free icons


No frameworks. No build tools. No dependencies. Just clean, portable web code.




🚀 Getting Started

Prerequisites


Any modern web browser (Chrome, Firefox, Edge, Safari)
A code editor if you plan to modify — VS Code recommended
No installations, servers, or package managers required


Setup Instructions


Clone the repository


bash   git clone https://github.com/your-username/studoc.git
   cd studoc


Open the project
Simply open index.html in your browser:


bash   # On Windows
   start index.html

   # On macOS
   open index.html

   # On Linux
   xdg-open index.html

Or use the Live Server extension in VS Code for auto-refresh on edits.


You're live!
No build step, no environment variables, no configuration needed.



📁 Project Structure

studoc/
│
├── index.html        # All pages and JavaScript logic
├── style.css         # Full styling, theming, and responsive layout
├── README.md         # Project documentation
└── LICENSE           # MIT License

All pages (Sign In, Home, Documents, Resume Builder, Community, About) live within index.html and are toggled via JavaScript — a single-page application (SPA) pattern without any framework.


🤝 Contributing Guidelines

Contributions are welcome and appreciated. Here's how to get involved:


Fork the repository
Create a feature branch


bash   git checkout -b feat/YourFeatureName


Make your changes and commit


bash   git commit -m "feat: describe what you added"


Push and open a Pull Request


bash   git push origin feat/YourFeatureName


Code style note: Keep JavaScript in plain ES6+. Avoid adding external dependencies unless absolutely necessary — Studoc's strength is its simplicity and portability.




🔮 Future Phases

The following features are planned for upcoming releases:


🔐 Real backend authentication with persistent user accounts.
☁️ Cloud storage integration so documents survive browser sessions.
🔔 Notifications for community replies and mentions.
🤝 Direct messaging between students.
📊 Document analytics — views, downloads, and engagement.
🌙 Light / dark mode toggle.
📱 Progressive Web App (PWA) support for mobile installation.
🤖 AI-powered document summarizer and study assistant.



📜 License

This project is licensed under the MIT License. See the LICENSE file for more details.


<div align="center">
<b>Built with ❤️ for students, by students — the Studoc Team</b>
</div>
