# Game Oracle 🔮

Game Oracle is a cutting-edge market analysis tool designed specifically to empower game developers. By transforming raw market data into actionable strategies, Game Oracle helps mitigate market risks and enhances the competitiveness of game projects on a global scale. 

Our system connects directly to the Steam Web API to process real-time game data—such as pricing, genres, tags, and reviews. We then pass this data through fine-tuned NLP models (like BERT/LLaMA) to generate highly accurate predictions regarding market saturation, optimal pricing, and overall project success probability.

## 🚀 Features

- **Steam Integration:** Live data ingestion via SteamWebAPI and SteamSpy for tags, prices, and reviews.
- **NLP Market Processing:** Automated sentiment analysis and success prediction using fine-tuned ML models.
- **Cynosure Dashboard:** A highly polished, cyberpunk-inspired "system terminal" interface built with React, Tailwind v4, and Recharts.
- **Market Telemetry:** Dynamic scatter plots and tag velocity tracking to pinpoint profitable niches.

---

## 🛠️ Tech Stack

- **Frontend:** React 19, Vite, Tailwind CSS v4, Lucide React, Recharts
- **Backend (Planned):** Python 3.12+, FastAPI, Uvicorn
- **Machine Learning (Planned):** `pandas`, `scikit-learn`, `feature-engine`, HuggingFace `transformers`

---

## 💻 Installation & Setup

Right now, the frontend "Cynosure" terminal is fully built and running on mock data. Here is how to get it running locally.

### 1. Clone the Repository
```bash
git clone https://github.com/kaesit/SteamAnalysisTool.git
cd SteamAnalysisTool
```

### 2. Run the Frontend Dashboard
Navigate to the frontend directory and install the required Node modules.

```bash
cd frontend
npm install
npm run dev
```

The application will start on `http://localhost:5173`.

### 3. Backend Setup (Coming Soon)
The Python/Django backend is currently in the architecture planning phase. Once deployed, it will handle the heavy NLP processing and connect to the Steam APIs. Stay tuned!

---

## 👥 The Team
- **Berkay Sabuncu**
- **Bilal Abiç**
- **Esad Abdullah Kösedağ**
- **Eren Bozyer**
- **Mert Can Yücedağ**

## 📄 License
This project is licensed under the GNU General Public License v3.0 - see the `LICENSE` file for details.