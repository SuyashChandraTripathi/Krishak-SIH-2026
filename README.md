## Krishak — One bridge, a fairer farm to market

**Smart India Hackathon 2026 | Problem Statement: SIH26033 | Team: Axiom**

Krishak is a digital farm-to-market platform designed to help farmers and Farmer Producer Organizations (FPOs) connect directly with retailers, consumers, bulk buyers, and institutional buyers. It aims to reduce unnecessary intermediaries, improve price transparency, and simplify agricultural produce transactions.

## Problem Statement

Farmers can face limited market access, price uncertainty, post-harvest losses, and dependence on multiple intermediaries. Small and marginal farmers may also struggle to aggregate enough produce to meet the requirements of larger buyers.

Krishak proposes a digital platform to make agricultural market access more transparent, accessible, and efficient.

## Our Solution

Krishak brings farmers and buyers onto a common digital marketplace, with features designed around transparent pricing, produce discovery, and simplified transactions.

## Key Features

- **Digital Marketplace:** Enables buyers to explore agricultural produce listed by farmers.
- **Farmer and FPO Listings:** Supports produce listings with quality-based pricing.
- **Transparent Pricing:** Designed to benchmark prices against mandi and e-NAM market rates rather than having the platform arbitrarily set prices.
- **FPO Aggregation:** Supports the concept of aggregating produce from nearby FPOs to help meet larger orders.
- **Simulated Digital Payments:** Demonstrates a payment flow with simulated UPI settlement; no real money is transferred in the current prototype.
- **Role-Based Access:** Separate interfaces for consumers/buyers, farmers, and administrators.
- **Dashboard and Analytics:** Uses visualizations to present platform information.
- **Logistics Concept:** Proposes nearby pickup hubs and route-batched deliveries to improve distribution efficiency.
- **AI-Enabled Opportunities:** Demand forecasting and route optimization are proposed areas for future enhancement, where not yet implemented in the current build.

## Technology Stack

| Component | Technology |
|---|---|
| Frontend and UI | Python, Streamlit, custom HTML and CSS |
| Backend Logic | Python modules |
| Database | SQLite |
| Data Processing | Pandas |
| Data Visualization | Altair |
| Image Processing and Assets | Pillow (PIL) |

## Project Structure

- `app.py` — Main Streamlit application
- `auth.py` — Authentication-related logic
- `db.py` — Database operations and initialization
- `pricing.py` — Pricing-related logic
- `payments.py` — Simulated payment logic
- `assets/` — Images and other visual assets
- `requirements.txt` — Python dependencies
- `README.md` — Project documentation

## Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/krishak-sih-2026.git
cd krishak-sih-2026
```

Replace `YOUR-USERNAME` with the GitHub username that owns the repository.

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Configure local demo data

Follow the project's setup instructions for any required local configuration or demo-user data. Do not publish real passwords, secrets, or private user information.

### 5. Run the application

```bash
python -m streamlit run app.py
```

Streamlit will display a local URL in the terminal, usually `http://localhost:8501`.

## Important Note

Krishak is an SIH 2026 prototype. Payments in the current prototype are simulated and do not process real transactions. Features described as proposed or future enhancements should not be interpreted as fully implemented functionality.

## Login Credentials

Username --> krishak@123
Password --> krishak@123

## Team

**Team Name:** Axiom
**Project:** Krishak  
**Event:** Smart India Hackathon 2026  
**Problem Statement ID:** SIH26033

---

*Krishak — One bridge, a fairer farm to market.*
