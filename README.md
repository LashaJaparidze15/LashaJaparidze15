# Lasha Japaridze

Final-year Software Development student at **SETU Carlow** (BSc Hons, graduating 2027), working remotely as a developer alongside my degree. I build full-stack apps and actually ship them: most of the projects below are deployed and running, not just sitting in a repo.

**Open to graduate software developer roles for 2027, including remote.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lasha-japaridze-651144252/)
[![Portfolio](https://img.shields.io/badge/Portfolio-10B981?style=flat&logo=vercel&logoColor=white)](https://portfolio-beige-xi-78.vercel.app/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:lashajapara68@gmail.com)

---

### Experience

**Software Developer (remote)**, health & wellness platform *(Feb 2026 to present, production)*
Sole developer on the platform, reporting to the CEO. I own the **Strapi + PostgreSQL** backend on Heroku, three **React** dashboards (clinical, university and sports), and the **React Native** member app on iOS and Android. Day to day that means REST APIs, membership and nutrition-plan logic, single sign-on between the app and the website, and health data integrations: Dexcom and FreeStyle Libre glucose syncs, Garmin, Fitbit and Apple Health.

### Open source

**[@fastify/http-proxy #472](https://github.com/fastify/fastify-http-proxy/pull/472)**: *merged into `main` by Fastify's lead maintainer.* Fixed a bug where a proxied request crashed entirely if an upstream response contained invalid HTTP header characters (control chars or code points > 0xFF). Added `sanitizeHeaderValue` / `sanitizeHeaders` utilities (handling both string and array values like `set-cookie`) with unit tests, now shipping in the published package.

### Currently building

**[SummitCast](https://github.com/LashaJaparidze15/summitcast)**: my final-year project. A route-aware mountain weather planner: upload a hillwalking route (GPX) and a start time, and it works out when you'll reach each point (Naismith's rule with descent corrections), pulls the Met Éireann forecast for that place at that time, and flags unsafe sections with data-driven hazard rules that explain every warning. Java 21 + Spring Boot backend, React + Leaflet frontend, JUnit tests.

**[Dublin Bikes predictor](https://github.com/LashaJaparidze15/dublin-bikes-predictor)**: answers "will station X have a bike in 30 minutes?". A scheduled GitHub Actions job collects live station data every 5 minutes into Postgres; LightGBM models trained on 18 months of history beat the naive baseline by 13% at 60 minutes. Served through a FastAPI endpoint and a Streamlit dashboard, with every live prediction logged and checked against what really happened.
&nbsp;&nbsp;**Live → [Streamlit dashboard](https://dublin-bikes-predictor-xemaugbi5xtyxcss4hkhzs.streamlit.app/)**

**[bizfinder.ie](https://github.com/LashaJaparidze15/bizfinder-ie)**: a national Irish business directory & analytics platform. Next.js SSR for SEO, an Expo mobile app, a Fastify API and Python scrapers, all on Supabase with PostGIS + pgvector and Stripe billing. Holds **46,000+ businesses across all 26 counties**, with semantic "similar business" search, first-party reviews and a business-owner claim flow.
&nbsp;&nbsp;**Live → [bizfinder-ie-web.vercel.app](https://bizfinder-ie-web.vercel.app)**

### Earlier projects

| Project | What it is | Stack | Live |
| --- | --- | --- | --- |
| **[DevConnect](https://github.com/LashaJaparidze15/devconnect)** | Developer networking platform with real-time chat | React · Node/Express · MongoDB · Socket.io · JWT | [demo](https://devconnect-virid-five.vercel.app) |
| **[Buddy](https://github.com/LashaJaparidze15/Buddy)** | Smart daily planner with tasks, weather, news & stock data | React · Python/FastAPI | [demo](https://buddy-lime.vercel.app) |
| **[Car Rental System](https://github.com/LashaJaparidze15/car-rental-company)** | Booking & fleet management system | PHP · MySQL | |
| **[Purchase Manager](https://github.com/LashaJaparidze15/purchase-manager)** | Inventory & vendor order tracking (desktop app) | Java · Swing · MySQL | |
| **[Surviving the Jungle](https://github.com/LashaJaparidze15/surviving-the-jungle)** | Text-adventure game written from scratch in Motorola 68000 assembly | M68K Assembly | |

### Tech I work with

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Strapi](https://img.shields.io/badge/Strapi-4945FF?style=flat&logo=strapi&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![Heroku](https://img.shields.io/badge/Heroku-430098?style=flat&logo=heroku&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
