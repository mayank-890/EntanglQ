# ⚛ EntangleQ — Quantum Secure Communication Platform

**Team Kernal Kush | IILM University Greater Noida | Hackathon 2025**

A fully interactive 3D web platform demonstrating quantum entanglement-based data security through BB84 QKD, Bell State simulation, ML-powered threat detection, and quantum-secured messaging.

---

## 🗂 Project Structure

```
entangleq/
├── index.html        ← 3D Landing Page (Three.js hero + feature showcase)
├── simulator.html    ← Full Interactive Quantum Simulator (5 tabs)
├── vercel.json       ← Vercel deployment config
└── README.md         ← This file
```

---

## 🚀 Deploy to Vercel (3 Methods)

### Method 1 — Vercel CLI (Recommended)

```bash
# 1. Install Vercel CLI
npm install -g vercel

# 2. Navigate to project folder
cd entangleq

# 3. Deploy (follow prompts)
vercel

# 4. For production deployment
vercel --prod
```

### Method 2 — Vercel Dashboard (Drag & Drop)

1. Go to [vercel.com](https://vercel.com) and sign up/log in
2. Click **"Add New Project"**
3. Drag the entire `entangleq/` folder onto the import area
4. Click **Deploy** — done!

### Method 3 — GitHub Integration

1. Push this folder to a GitHub repository:
   ```bash
   git init
   git add .
   git commit -m "feat: EntangleQ 3D quantum platform"
   git remote add origin https://github.com/YOUR_USERNAME/entangleq.git
   git push -u origin main
   ```
2. Go to [vercel.com](https://vercel.com) → Import Project → connect GitHub
3. Select your repository → Deploy

---

## 🧰 Open in Google Project IDX

1. Go to [idx.google.com](https://idx.google.com)
2. Click **"Import a Repo"** or **"Open local folder"**
3. Upload/paste the project files
4. Open `index.html` in the built-in browser preview
5. No build step needed — pure HTML/JS/CSS

### Run locally with IDX Live Preview:
- Open any `.html` file
- Click **"Show Preview"** in the toolbar
- IDX will serve the file on a local port with hot reload

---

## ⚛ Features

| Module | Description |
|--------|-------------|
| **3D Landing Page** | Three.js quantum entanglement network — interactive drag-to-rotate |
| **BB84 QKD Simulator** | Full protocol with qubit-by-qubit visualization |
| **Entanglement Lab** | Bell state Φ⁺ construction & measurement with statistics chart |
| **ML Threat Engine** | Random Forest classifier for QBER-based eavesdropper detection |
| **Secure Channel** | XOR-cipher message encryption using the generated quantum key |
| **Analytics Dashboard** | QBER trends, key-bit history, session logs |

---

## 🔧 Technical Stack

- **Three.js r128** — 3D quantum network visualization (CDN)
- **Orbitron / Share Tech Mono / Rajdhani** — Typography (Google Fonts)
- **Vanilla JS** — All simulation logic (zero dependencies)
- **Canvas 2D API** — Charts, particle background, qubit state graphs
- **CSS3** — Animations, glass morphism, responsive grid

---

## 🌐 Live URL Structure

After Vercel deployment:
- `https://entangleq.vercel.app/` → 3D Landing Page
- `https://entangleq.vercel.app/simulator` → Full Simulator

---

## 📡 How Quantum Entanglement Secures Data

1. **Superposition** — Qubits exist as |0⟩ + |1⟩ simultaneously until measured
2. **Entanglement** — Measuring one qubit instantly collapses the partner's state
3. **No-Cloning Theorem** — Eve cannot copy qubits without disturbing them
4. **BB84 Protocol** — Key bits are sifted from matching measurement bases
5. **QBER Monitoring** — Any interception raises error rate above 11% threshold

---

*Built with quantum physics, Three.js, and a lot of entanglement.*
