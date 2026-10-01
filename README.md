# Triple-Guard 🛡️

### AI-Powered Phishing Detection and Prevention System

Triple-Guard is a web-based phishing detection and prevention system designed to identify potentially malicious or fraudulent URLs and help users recognize phishing threats before interacting with them.

The project focuses on combining automated analysis with a user-friendly interface to provide fast and understandable phishing-risk information.

---
---

## 💡 Proposed Solution

Triple-Guard provides a phishing detection and prevention workflow where a suspicious URL can be submitted for analysis.

```text
                 ┌─────────────────┐
                 │      USER       │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │  Suspicious URL │
                 │     Input       │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ URL Processing  │
                 │ & Validation    │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ Threat Analysis │
                 │     Engine      │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ Phishing Risk   │
                 │   Assessment    │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ Detection /     │
                 │ Prevention      │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ User Warning /  │
                 │ Security Result │
                 └─────────────────┘
```

---

## 🛡️ Key Features

- 🔍 **Phishing URL Detection**
  - Analyze suspicious URLs
  - Identify potentially malicious links

- 🚨 **Threat Identification**
  - Detect indicators associated with phishing attacks
  - Provide security-focused results

- 🛡️ **Phishing Prevention**
  - Warn users about potentially unsafe links
  - Help users make informed decisions before accessing suspicious websites

- 🌐 **Web-Based Interface**
  - User-friendly interface
  - Simple URL analysis workflow

- ⚡ **Fast Analysis**
  - Designed for quick phishing-risk assessment

- 📊 **Security Results**
  - Presents detection results in an understandable format

---

## 🏗️ System Architecture

```text
┌──────────────────────────────────────┐
│              USER                    │
│                                      │
│        Suspicious URL                │
└──────────────────┬───────────────────┘
                   │
                   ▼
┌──────────────────────────────────────┐
│          WEB INTERFACE               │
│                                      │
│       URL Input & Validation         │
└──────────────────┬───────────────────┘
                   │
                   ▼
┌──────────────────────────────────────┐
│        PHISHING ANALYSIS             │
│                                      │
│   URL / Threat Feature Analysis      │
└──────────────────┬───────────────────┘
                   │
                   ▼
┌──────────────────────────────────────┐
│        DETECTION ENGINE              │
│                                      │
│      Phishing Risk Assessment        │
└──────────────────┬───────────────────┘
                   │
                   ▼
┌──────────────────────────────────────┐
│        PREVENTION LAYER              │
│                                      │
│     Warning / Security Response      │
└──────────────────┬───────────────────┘
                   │
                   ▼
┌──────────────────────────────────────┐
│             USER                     │
│                                      │
│      Detection Result                │
└──────────────────────────────────────┘
```

---

## 🔄 Detection Workflow

```text
URL Submission
      │
      ▼
URL Validation
      │
      ▼
Feature / Threat Analysis
      │
      ▼
Phishing Detection
      │
      ▼
Risk Assessment
      │
      ├───────────────┐
      │               │
      ▼               ▼
   SAFE           SUSPICIOUS
      │               │
      ▼               ▼
  Continue         Warning
                   / Block
```

---

# 🛠️ Tech Stack

### Frontend

- React
- JavaScript / TypeScript
- HTML
- CSS

### Build & Package Management

- Vite
- npm
- Bun

### Development Tools

- Git
- GitHub
- Visual Studio Code

### Security Domain

- Phishing Detection
- URL Analysis
- Threat Detection
- Cybersecurity

---

# 📂 Project Structure

The repository contains the following major components:

```text
Triple-guard/
│
├── .env
├── .gitignore
├── LICENSE
├── README.md
│
├── components.json
├── eslint.config.js
├── favicon.ico
├── index.html
│
├── package.json
├── package-lock.json
├── bun.lockb
│
├── postcss.config.js
├── robots.txt
│
└── src/
    └── Application Source Code
```

### Directory / File Description

| File / Directory | Purpose |
|---|---|
| `src/` | Main application source code |
| `package.json` | Project dependencies and scripts |
| `package-lock.json` | npm dependency lock file |
| `bun.lockb` | Bun dependency lock file |
| `components.json` | Component configuration |
| `eslint.config.js` | ESLint configuration |
| `postcss.config.js` | PostCSS configuration |
| `index.html` | Application entry HTML |
| `.gitignore` | Git ignored files |
| `.env` | Environment configuration |
| `LICENSE` | MIT License |
| `README.md` | Project documentation |

---

# ⚙️ Installation & Setup

## Prerequisites

Install the following before running the project:

- Node.js
- npm
- Git
- Visual Studio Code (recommended)

Verify Node.js:

```bash
node --version
```

Verify npm:

```bash
npm --version
```

Verify Git:

```bash
git --version
```

---

## 1. Clone the Repository

```bash
git clone https://github.com/joshna1210/Triple-guard.git
```

---

## 2. Navigate to the Project

```bash
cd Triple-guard
```

---

## 3. Install Dependencies

Using npm:

```bash
npm install
```

The repository contains `package.json` and `package-lock.json`, so npm can install the project's dependencies.

---

## 4. Environment Configuration

The project contains an `.env` file.

If environment variables are required by the application, configure them according to the project's implementation before starting the development server.

> **Security:** Never commit API keys, passwords, tokens, or other secrets to GitHub. Store sensitive values in environment variables.

---

# ▶️ Running the Application

Start the development server:

```bash
npm run dev
```

Vite will provide a local development URL in the terminal.

Typically, the application can be accessed at:

```text
http://localhost:5173
```

Open the displayed URL in your browser.

---

# 🧪 Development Workflow

After starting the application:

```text
Open Application
       │
       ▼
Enter Suspicious URL
       │
       ▼
Submit URL
       │
       ▼
Analyze URL
       │
       ▼
Phishing Detection
       │
       ▼
Risk Assessment
       │
       ▼
Display Security Result
```

---

# 🔍 Phishing Detection

The system is designed to help identify potentially malicious URLs by analyzing available indicators associated with phishing activity.

Potential indicators can include:

- Suspicious URL structure
- Unusual domain characteristics
- Deceptive URL patterns
- Suspicious redirects
- Known phishing indicators
- Other security-related URL characteristics

The exact detection logic depends on the implementation of the project.

---

# 🛡️ Prevention

Triple-Guard focuses not only on identifying suspicious URLs but also on helping users avoid interacting with potentially dangerous links.

Possible prevention responses include:

```text
Safe
 │
 └── User can continue

Suspicious
 │
 └── Display Warning

Malicious
 │
 └── Prevent / Block Access
```

---

# 🎯 Project Objectives

The main objectives of Triple-Guard are:

1. Detect potentially malicious phishing URLs.
2. Analyze suspicious URL characteristics.
3. Provide users with understandable security information.
4. Reduce the risk of users interacting with phishing links.
5. Demonstrate the use of AI and cybersecurity techniques for phishing detection.
6. Build an accessible web-based security solution.

---

# 📊 Security Use Cases

Triple-Guard can be used as a demonstration platform for:

- Phishing URL detection
- Cybersecurity awareness
- Suspicious link analysis
- Threat detection
- Security education
- URL risk assessment
- Phishing prevention

---

# 🚀 Future Enhancements

Potential future improvements include:

- 🤖 Advanced machine-learning-based phishing classification
- 🧠 NLP-based analysis of suspicious website content
- 🌐 Browser extension integration
- 📧 Email phishing detection
- 📱 Mobile application
- 🔗 Real-time URL reputation analysis
- 📊 Security analytics dashboard
- 🚨 Real-time threat alerts
- 🗃️ Larger phishing URL datasets
- 🔐 Improved privacy and secure data handling
- 🔄 Continuous model improvement

---

# 🔐 Security & Privacy

Triple-Guard is designed as a cybersecurity project for phishing detection and prevention.

When extending the project:

- Do not store sensitive user information unnecessarily.
- Do not expose API keys or credentials.
- Keep secrets in environment variables.
- Validate external inputs.
- Use secure communication when integrating external services.
- Regularly update project dependencies.

---

# 🧪 Testing

Before deployment, test the application with different URL categories such as:

```text
Legitimate URLs
      │
      ▼
Expected: Safe / Low Risk
```

```text
Suspicious URLs
      │
      ▼
Expected: Warning / Suspicious
```

```text
Known Malicious URLs
      │
      ▼
Expected: Malicious / Block
```

Only use safe, controlled test data when evaluating the system.

---

# 🛠️ Troubleshooting

## Node.js Not Found

Check your installation:

```bash
node --version
```

If Node.js is not recognized, install Node.js and restart your terminal.

---

## npm Install Error

Try:

```bash
npm cache verify
```

Then:

```bash
npm install
```

---

## Development Server Does Not Start

Make sure you are inside the project directory:

```bash
cd Triple-guard
```

Then run:

```bash
npm run dev
```

---

## Port Already in Use

If the default Vite port is unavailable, Vite may automatically select another available port.

Check the terminal output for the correct local URL.

---

# 📌 Project Information

**Project Name:** Triple-Guard

**Category:** Cybersecurity

**Application:** Phishing Detection and Prevention System

**Type:** Web Application

**Primary Technology:** JavaScript / React

**Build Tool:** Vite

**Repository:**

https://github.com/joshna1210/Triple-guard

---

# 👩‍💻 Developer

## Joshna Rose J.N

**B.E. Computer Science Engineering – Cyber Security**  
**St. Joseph's College of Engineering**

### Areas of Interest

- 🔐 Cyber Security
- 🤖 Artificial Intelligence
- 🧠 Machine Learning
- 🌐 Full-Stack Development
- 🛡️ Threat Detection
- 🔍 Cyber Threat Intelligence
- ☁️ Cloud Computing

---
---

# 📄 License

This project is licensed under the **MIT License**.

See the [LICENSE](LICENSE) file for the full license text.

---

## ⭐ Support

If you find this project useful or interesting, consider giving the repository a ⭐ on GitHub.

Thank you for visiting **Triple-Guard**! 🛡️
