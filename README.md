# Brain Face 🧠

A responsive React application that detects faces in images. This project demonstrates frontend development skills using React, Tachyons for styling, and particle animations.

> **Note**: This is a **standalone demo version** of the original application. Backend authentication and API calls have been mocked to allow for easy viewing and deployment without a server.

## Features ✨

- **Face Detection**: Draws a bounding box around faces in provided image URLs (simulated for demo).
- **Responsive Design**: Built with Tachyons CSS for a mobile-first layout.
- **Interactive UI**: Includes particle background animations (`react-tsparticles`).
- **Mock Authentication**: simulated Sign In and Registration flows.

## Tech Stack 🛠️

- **React** (v16+)
- **Create React App**
- **Tachyons** (CSS Toolkit)
- **tsparticles** (Animations)

## Getting Started 🚀

### Prerequisites
- Node.js installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/nic-ball/brain-face.git
   cd brain-face
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the application:
   ```bash
   npm start
   ```
   Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Deployment 🌐

This project is configured for easy deployment to **GitHub Pages**.

1. Open `package.json` and ensure the `homepage` field matches your repository URL:
   ```json
   "homepage": "https://<YOUR_GITHUB_USERNAME>.github.io/brain-face"
   ```

2. Run the deployment script:
   ```bash
   npm run deploy
   ```

## Usage 💡

1. **Sign In**: Enter any email and password (e.g., `test@test.com`, `password`) to enter.
2. **Register**: Requires a name, email, and password to simulate account creation.
3. **Detect Faces**: Paste an image URL into the input field and click **Detect**. A box will be drawn around the face!

---
*Updated for Portfolio Demo - 2025*
