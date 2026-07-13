# Roomify 🛋️✨

Roomify is an AI-powered interior design and 3D visualization tool that lets you seamlessly transform your spaces. Built for modern web experiences, it allows users to upload a photo of a room, process it, and dynamically compare the original vs. the AI-rendered version.

🌐 **Live Demo:** [Roomify on Puter](https://puter.com/app/roomify-fiwc)

## ✨ Highlights

- 🎨 **AI-Powered Visualization** — Transform basic room photos into stunning 3D renders.
- 📸 **Interactive Before & After** — Compare designs effortlessly with a draggable slider.
- ⚡ **Lightning Fast UI** — Built on React 19 & React Router v8 for optimal performance.
- 💅 **Modern Styling** — Beautiful, responsive design using TailwindCSS v4.
- 🔄 **Real-Time Render State** — Animated loading and visual cues during image generation.
- 📱 **Fully Responsive** — Works flawlessly on desktop and mobile devices.

### 🌐 Powered by Puter.js
This project heavily leverages **[Puter.js](https://puter.com)** for its backend infrastructure, eliminating the need for a traditional server:
- 🔐 **Puter Auth** — Provides instant, secure authentication and user session management.
- 🗄️ **Puter Hosting / DB** — Handles storing user data, saving projects, and securely hosting the before/after images in the cloud.
- ⚙️ **Puter Workers** — Acts as the secure backend API, executing server-side logic and background tasks to process and manage user projects.

## 🛠️ Tech Stack

- **Framework:** React Router v8 (React 19)
- **Styling:** TailwindCSS v4
- **Backend & Auth:** Puter.js & Puter Workers
- **Icons:** Lucide React
- **Components:** React Compare Slider
- **Language:** TypeScript
- **Bundler:** Vite

## 🚀 Getting Started

### Prerequisites

Ensure you have Node.js installed.

### Installation

1. Clone the repository and navigate into the directory:
```bash
git clone https://github.com/your-username/roomify.git
cd roomify
```

2. Install the dependencies:
```bash
npm install
```

3. Set up Environment Variables:
Before running the application, copy the `.env.example` file to `.env.local` and fill in the required values (like your Puter Worker URL).
```bash
cp .env.example .env.local
```

### Development

Start the development server with HMR:
```bash
npm run dev
```

Your application will be available at `http://localhost:5173`.

## 📦 Building for Production

Create a production build:
```bash
npm run build
```

## ☁️ Deployment

Roomify is built to be easily deployed. For a fast cloud deployment, consider using [Puter](https://puter.com/) as the primary hosting and backend solution, or deploy the output of `npm run build` to your favorite static host.

---

Built with ❤️ using React Router and Puter.js.
