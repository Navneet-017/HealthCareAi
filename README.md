<div align="center">

# 🏥 Healthcare

### *AI-Powered Digital Health Platform for Underserved Communities*

[![Next.js](https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![OpenAI](https://img.shields.io/badge/OpenAI-Powered-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com/)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge)](http://makeapullrequest.com)

---

**🌍 Breaking barriers in healthcare access through AI innovation**

[✨ Features](#-features) • [🚀 Quick Start](#-quick-start) • [🛠️ Tech Stack](#️-tech-stack) • [📖 Documentation](#-documentation) • [🤝 Contributing](#-contributing)

</div>

---

## 🎯 Problem Statement

> **2.4 billion people** worldwide lack access to basic healthcare services. Language barriers, geographical isolation, and limited infrastructure create life-threatening gaps in medical care.

**Hackaxios Healthcare** bridges this gap with an AI-powered platform that delivers:
- 🩺 Intelligent symptom analysis in **7+ languages**
- 📹 Telemedicine consultations for remote areas
- 📱 SMS-based health support for low-connectivity regions
- 🚨 Automated emergency detection and alerts

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🤖 AI-Powered Diagnosis
- Advanced symptom analysis using OpenAI
- Risk assessment with severity scoring
- Personalized health recommendations
- Smart triage and emergency detection

</td>
<td width="50%">

### 🌐 Multilingual Support
- **7 Languages**: EN, ES, FR, PT, HI, AR, SW
- Real-time translation
- Culturally-aware health guidance
- RTL language support (Arabic)

</td>
</tr>
<tr>
<td width="50%">

### 📹 Telemedicine Platform
- HD video consultations
- Screen sharing & annotations
- Digital prescriptions
- Appointment scheduling

</td>
<td width="50%">

### 📱 SMS Health Assistant
- Health guidance via text messages
- Works without internet
- Emergency alert system
- Medication reminders

</td>
</tr>
<tr>
<td width="50%">

### 📊 Health Analytics Dashboard
- Community health monitoring
- Disease outbreak tracking
- Population health insights
- Predictive analytics

</td>
<td width="50%">

### 🔒 Enterprise Security
- HIPAA-compliant architecture
- End-to-end encryption
- Secure authentication (NextAuth.js)
- Comprehensive audit logging

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

| Category | Technologies |
|:--------:|:-------------|
| **Frontend** | ![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=next.js&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Framer](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white) |
| **Backend** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=flat-square&logo=mongoose&logoColor=white) |
| **AI/ML** | ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white) ![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=groq&logoColor=white) |
| **Communication** | ![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white) ![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socket.io&logoColor=white) ![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white) |
| **DevOps** | ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) ![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) |

</div>

---

## 🚀 Quick Start

### Prerequisites

- **Node.js** 18+ 
- **MongoDB** (local or Atlas)
- **OpenAI API Key**
- **Twilio Account** (optional, for SMS)

### Installation

```bash
# 1️⃣ Clone the repository
git clone https://github.com/your-username/Hackaxios-Healthcare.git
cd Hackaxios-Healthcare/healthcare

# 2️⃣ Install dependencies
npm install

# 3️⃣ Configure environment variables
cp .env.example .env.local
# Edit .env.local with your API keys

# 4️⃣ Start development server
npm run dev
```

### Environment Variables

```env
# 🗄️ Database
MONGODB_URI=mongodb://localhost:27017/hackaxios-healthcare

# 🔐 Authentication
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your-secret-key

# 🤖 AI Services
OPENAI_API_KEY=sk-your-openai-key

# 📱 SMS (Optional)
TWILIO_ACCOUNT_SID=your-twilio-sid
TWILIO_AUTH_TOKEN=your-twilio-token
TWILIO_PHONE_NUMBER=+1234567890
```

### 🌐 Access the Application

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📁 Project Structure

```
HealthCareAi
├── 📂 healthcare/                 # Main application
│   ├── 📂 src/
│   │   ├── 📂 app/               # Next.js App Router
│   │   │   ├── 📂 [locale]/      # Internationalized pages
│   │   │   │   ├── 📂 admin/           # Admin dashboard
│   │   │   │   ├── 📂 auth/            # Authentication pages
│   │   │   │   ├── 📂 consultations/   # Telemedicine
│   │   │   │   ├── 📂 dashboard/       # User dashboard
│   │   │   │   ├── 📂 health-records/  # Medical records
│   │   │   │   ├── 📂 provider/        # Provider portal
│   │   │   │   ├── 📂 sms-support/     # SMS interface
│   │   │   │   └── 📂 symptom-checker/ # AI diagnosis
│   │   │   └── 📂 api/           # REST API endpoints
│   │   ├── 📂 components/        # React components
│   │   ├── 📂 lib/               # Utilities & services
│   │   ├── 📂 models/            # MongoDB schemas
│   │   └── 📂 types/             # TypeScript definitions
│   ├── 📂 messages/              # i18n translations
│   │   ├── 🇺🇸 en.json
│   │   ├── 🇪🇸 es.json
│   │   ├── 🇫🇷 fr.json
│   │   ├── 🇵🇹 pt.json
│   │   ├── 🇮🇳 hi.json
│   │   ├── 🇸🇦 ar.json
│   │   └── 🇹🇿 sw.json
│   └── 📂 public/                # Static assets
└── 📄 README.md                  # You are here! 👋
```

---

## 🧪 Testing

```bash
# Run all tests
npm test

# Unit tests
npm run test:unit

# Integration tests
npm run test:integration

# E2E tests with Playwright
npm run test:e2e

# Test coverage report
npm run test:coverage
```

---

## 🌍 Supported Languages

| Language | Code | Status | RTL |
|:---------|:----:|:------:|:---:|
| 🇺🇸 English | `en` | ✅ Complete | No |
| 🇪🇸 Spanish | `es` | ✅ Complete | No |
| 🇫🇷 French | `fr` | ✅ Complete | No |
| 🇵🇹 Portuguese | `pt` | ✅ Complete | No |
| 🇮🇳 Hindi | `hi` | ✅ Complete | No |
| 🇸🇦 Arabic | `ar` | ✅ Complete | Yes |
| 🇹🇿 Swahili | `sw` | ✅ Complete | No |

---

## 📖 Documentation

| Document | Description |
|----------|-------------|
| [📚 API Reference](./healthcare/docs/api.md) | Complete API documentation |
| [🚀 Deployment Guide](./healthcare/docs/deployment.md) | Production deployment |
| [👥 User Manual](./healthcare/docs/user-guide.md) | End-user documentation |
| [🔧 Developer Guide](./healthcare/docs/developer.md) | Development setup |

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

1. **🍴 Fork** the repository
2. **🌿 Create** a feature branch: `git checkout -b feature/amazing-feature`
3. **💾 Commit** your changes: `git commit -m 'Add amazing feature'`
4. **📤 Push** to the branch: `git push origin feature/amazing-feature`
5. **🔀 Open** a Pull Request

### Guidelines
- Follow TypeScript best practices
- Write tests for new features
- Ensure accessibility (WCAG 2.1)
- Update documentation

---

## 👥 Team Hackaxios

<div align="center">

| Role | Responsibility |
|------|----------------|
| 🎨 **Frontend** | UI/UX, React Components, Animations |
| ⚙️ **Backend** | API, Database, Authentication |
| 🤖 **AI/ML** | Symptom Analysis, NLP, Recommendations |
| 📱 **Integration** | Twilio SMS, WebRTC, Socket.io |

</div>

---

## ⚠️ Medical Disclaimer

> **Important**: This platform is designed to supplement, not replace, professional medical care. In case of medical emergencies, please contact your local emergency services immediately.

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

## 🌟 Star History

If you find this project useful, please consider giving it a ⭐!

---

### 💙 Built with passion for global health equity

![Made with Love](https://img.shields.io/badge/Made_with-❤️-red?style=for-the-badge)
![For Healthcare](https://img.shields.io/badge/For-Healthcare-0066CC?style=for-the-badge)
![Open Source](https://img.shields.io/badge/Open-Source-brightgreen?style=for-the-badge)

**🏆 Hackathon 2025 Project by Team Hackaxios**

---

<sub>©All rights reserved.</sub>

</div>
