# 🚀 ShipSmart AI

**An AI-powered supply chain assistant for disruption detection and intelligent route optimization.**

## 👥 Team

| Field | Value |
|---|---|
| **Team Name** | RouteX AI |
| **Track** |  AI  |
| **Team Lead** | Shraddha Darekar – darekarshraddha5706@gmail.com |
| **Members** | Shraddha Darekar, Ved Bhojani ,Misbah Khokhar, Kirtan Chauhan|

---

## 🎯 Problem Statement


ShipSmart AI addresses supply chain disruptions that can delay shipments, reduce fleet utilisation, and create cold-chain compliance risks. Logistics teams need a faster way to identify affected shipments, recommend alternative routes, redeploy idle fleet assets, and detect temperature excursions.

---



## 💡 Solution

> ShipSmart AI is an AI-powered supply chain assistant that helps logistics teams identify shipments affected by disruptions and recommend suitable alternative routes. It also helps identify idle fleet assets and monitor cold-chain temperature alerts so teams can respond faster and reduce operational risks.

---

## ✨ Key Features

- **Disruption Detection:** Identifies shipments affected by active supply chain disruptions.
- **Shipment Risk Analysis:** Highlights shipments that may face delays or operational risks.
- **AI Route Recommendation:** Suggests alternative routes for affected shipments using AI.
- **Fleet Optimisation:** Identifies idle fleet assets that can be redeployed.
- **Cold-Chain Monitoring:** Detects temperature excursions and highlights potential compliance risks.

---

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| **Languages** | Python, HTML, CSS, JavaScript |
| **Frameworks** | Flask |
| **IBM Technologies** | IBM watsonx.ai, IBM Bob |
| **Databases** | SQLite |
| **Other** | GitHub, GitHub Actions |

---

## 📁 Repository Structure

```
├── src/                  # All source code
├── docs/                 # Written documentation
│   ├── problem-statement.md
│   ├── solution-overview.md
│   ├── architecture.md
│   └── setup-guide.md
├── demo/                 # Demo artifacts
│   ├── screenshots/      # App screenshots
│   └── demo-video-link.txt  # Link to demo video
├── presentation/         # Slide deck
└── ├── submission.yaml       # Structured submission metadata
└── README.md             # This file
```

---

## ⚡ How to Run

### Prerequisites
- Python 3.8+
- Flask
- SQLite3

### Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/darekarshraddha5706-hash/bob-ai-hackathon-CodeWarriors.git
cd bob-ai-hackathon-CodeWarriors

# 2. Install dependencies
pip install -r requirements.txt

# 3. Configure environment
cp .env.example .env
# Edit .env with your configuration values

# 4. Initialize database
python src/init_db.py

# 5. Run the application
python src/app.py
```

The application will be available at `http://localhost:5000`

---

## 🖥️ Demo

| Artifact | Status |
|---|---|
| 📹 Demo Video | In progress |
| 🌐 Live Demo | Development build |
| 🖼️ Screenshots | See `demo/screenshots/` |
| 📊 Presentation | See `presentation/` |



---

## ⚠️ Known Limitations

- The initial version uses sample logistics and fleet data.
- Real-time external logistics and IoT data integration is not included in the initial prototype.
- Authentication and production-level security are not implemented in this prototype.
- API rate limiting for IBM watsonx.ai is not yet configured for production scale. 

---

## 🏅 What We're Most Proud Of

We are proud of bringing disruption detection, shipment risk analysis, route recommendation, fleet optimisation, and cold-chain monitoring together in one practical platform. The integration of IBM watsonx.ai enables intelligent decision support that helps logistics teams respond faster to supply chain disruptions.

---

## 📚 Documentation

For detailed documentation, see:
- **Problem Statement:** [docs/problem-statement.md](docs/problem-statement.md)
- **Solution Overview:** [docs/solution-overview.md](docs/solution-overview.md)
- **Architecture:** [docs/architecture.md](docs/architecture.md)
- **Setup Guide:** [docs/setup-guide.md](docs/setup-guide.md)

---

## 📝 License

This project was created for the IBM Bob AI Hackathon 2026.

---

**Last Updated:** September 2026
