# MonteLab

MonteLab is an open-source platform for structured experimentation in stock price forecasting.  
It lets users define predictive targets, select or engineer features, train models, and evaluate outcomes — all in a transparent, reproducible environment.

Like markets. Like life. Probabilistic, not perfect.

---

## Features

- Pull and store historical stock price data
- Build custom prediction targets (e.g., “price > +2% in 5 days”)
- Engineer features: RSI, moving averages, price deltas, custom indicators
- Train ML models (Logistic Regression, Random Forest, XGBoost)
- Evaluate results: confusion matrix, ROC, signal overlay
- Save and compare experiments
- User-specific configs, saved runs, and metrics

---

## Tech Stack

| Layer       | Technology                     |
|-------------|-------------------------------|
| Frontend    | Next.js, TypeScript, TailwindCSS |
| Backend     | FastAPI, SQLAlchemy, Pydantic |
| Data & ML   | PostgreSQL, pandas, scikit-learn, XGBoost |
| Auth        | JWT (OAuth2 optional)         |
| DevOps      | Docker, GitHub Actions, Fly.io / Vercel |

---

## Project Structure

```plaintext
montelab/
├── backend/       # FastAPI app
├── frontend/      # Next.js + Tailwind UI
├── scripts/       # Data fetchers, seeders
├── docker-compose.yml
├── LICENSE
└── README.md
