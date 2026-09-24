<div align="center">
  <img src="https://raw.githubusercontent.com/nyandajr/nyandajr/main/banner.gif" width="100%" alt="Freddy Nyanda – ML Engineer Circuit Banner"/>
</div>

<br/>

<div align="center">

# Freddy Nyanda 🇹🇿

**Data Scientist · ML Engineer**
*Dar es Salaam, Tanzania*

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=15&pause=1300&color=00BFFF&center=true&vCenter=true&width=640&lines=I+don%27t+trust+a+data+source+until+I%27ve+verified+it+live;Found+committers.top+ranking+farmed+commits+%232+%E2%86%92+built+a+real+one;Found+OpenSky%27s+East+Africa+coverage+was+a+dead+zone+%E2%86%92+went+global;Open+to+ML+Engineer+%2F+Data+Scientist+roles)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/freddy-nyanda-971233204/)
[![Portfolio](https://img.shields.io/badge/Portfolio-00BFFF?style=flat-square&logo=github&logoColor=white)](https://nyandajr.github.io/portfolio_site/)
[![Email](https://img.shields.io/badge/ProtonMail-8B89CC?style=flat-square&logo=protonmail&logoColor=white)](mailto:freddynyanda@proton.me)
![2026 Contributions](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fgithub-contributions-api.jogruber.de%2Fv4%2Fnyandajr%3Fy%3D2026&query=%24.total.2026&style=flat-square&label=2026%20contributions&color=00bfff&labelColor=050b18&logo=github)

</div>

---

### 🔍 What actually makes these projects different

Most of the trackers below started the same way: I went looking for the "obvious" data source, checked what it actually returned, and found it was wrong — then built something that verifies itself instead of trusting the label on the tin.

| Assumed | Found on inspection | Response |
|---|---|---|
| committers.top's Tanzania #2 was a top contributor | ~137,000 commits, messages literally `"commit 5000"`, all in the same second — and the site itself hadn't updated in 3 weeks | Built [**East Africa Dev Ledger**](https://nyandajr.github.io/east-africa-dev-leaderboard-/) — real GitHub GraphQL numbers, refreshed every 5 days, farming pattern documented not hidden |
| OpenSky had usable East Africa flight coverage | A bounding box over the whole region returned **2** tracked aircraft vs. 735 in a same-size European box — the receivers just aren't there | Rebuilt [**Flight Emissions Tracker**](https://nyandajr.github.io/global-flight-emissions-tracker/) as a global tracker with the coverage gap itself reported as a data point |
| NewsAPI's free tier covered Kenya/Tanzania/Uganda | ~0.75% of "East Africa" rows were even regionally labeled, and those were AP wire stories, not local outlets | Rebuilt [**News Sentiment**](https://eastafricanewssentiment.streamlit.app) on a per-country-verified source mix |

---

### 🛠️ Featured Projects

<table>
<tr><td width="50%" valign="top">

**🗺️ [Strait of Hormuz Monitor](https://github.com/nyandajr/hormuz-strait-monitor)**
Live AIS vessel tracking through the strait, cross-referenced against Brent crude — independently confirmed real vessel silence against a live control strait, not an assumption.
`Python` `AIS/WebSockets` `Oracle Cloud`
🔴 [Live](https://nyandajr.github.io/hormuz-strait-monitor)

</td><td width="50%" valign="top">

**📈 [EA Financial Tracker](https://github.com/nyandajr/ea-financial-tracker)**
TZS/KES/UGX + BTC/ETH/BNB tracking with ML forecasting, crypto every 30 min, FX hourly.
`Python` `Streamlit` `Scikit-learn`
🔴 [Live](https://ea-financial-tracker.streamlit.app)

</td></tr>
<tr><td width="50%" valign="top">

**⛽ [Global Fuel Watch](https://github.com/nyandajr/global-fuel-watch)**
Petrol/diesel/LPG/crude across 20 countries — split-cadence pipeline built around a hard-learned 25-request/day crude API quota.
`Python` `Pandas` `Self-hosted Cron`

</td><td width="50%" valign="top">

**🛰️ [DSN Anomaly Tracker](https://github.com/nyandajr/dsn-anomaly-tracker)**
NASA Deep Space Network signal monitoring with live anomaly scoring.
`Python` `Streamlit` `MLOps`
🔴 [Live](https://dsn-anomaly-tracker.streamlit.app)

</td></tr>
<tr><td width="50%" valign="top">

**🌦️ [Tanzania Climate Watch](https://github.com/nyandajr/tanzania-climate-watch)**
5-city weather anomaly detection, ML forecasting, 15-min refresh — caught real pressure anomalies in Dar and Zanzibar during testing.
`Python` `Scikit-learn` `Self-hosted Cron`

</td><td width="50%" valign="top">

**✈️ [Global Flight Emissions Tracker](https://github.com/nyandajr/global-flight-emissions-tracker)**
Live global aircraft tracking with modeled per-flight-phase CO2 estimates.
`Python` `OpenSky API`
🔴 [Live](https://nyandajr.github.io/global-flight-emissions-tracker)

</td></tr>
<tr><td width="50%" valign="top">

**📰 [East Africa News Sentiment](https://github.com/nyandajr/East_Africa_News_Sentiment)**
Regional news sentiment via VADER, on a source mix verified per-country, not per-API-response-code.
`Python` `NLP` `VADER`
🔴 [Live](https://eastafricanewssentiment.streamlit.app)

</td><td width="50%" valign="top">

**🏆 [East Africa Dev Ledger](https://github.com/nyandajr/east-africa-dev-leaderboard-)**
GitHub GraphQL-verified developer leaderboard for Tanzania, Kenya & Uganda — built after finding the incumbent leaderboard stale and gameable.
`Python` `GitHub GraphQL`
🔴 [Live](https://nyandajr.github.io/east-africa-dev-leaderboard-/)

</td></tr>
</table>

---

### ⚙️ Core Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apache-spark&logoColor=white)
![SQL](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-00BFFF?style=flat-square&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

### 📊 Stats

<div align="center">

<!--START_SECTION:metrics-->
<img src="https://raw.githubusercontent.com/nyandajr/nyandajr/main/github-metrics.svg" alt="GitHub metrics" width="100%"/>
<!--END_SECTION:metrics-->

</div>

<sub>Self-hosted via a scheduled GitHub Action that commits this SVG straight to the repo — same reasoning as every tracker above: a third-party widget going down (or hitting its free-tier billing cap, as the last version of this graph did) isn't a risk worth carrying when self-hosting it is one workflow file.</sub>

---

<div align="center">

"Build in silence. Let the commits speak."

![Profile Views](https://komarev.com/ghpvc/?username=nyandajr&color=00bfff&style=flat-square&label=PROFILE+VIEWS)

</div>
