# Smart India Hackathon Workshop
# Date:20/09/2025
## Register Number:25017318
## Name:Darshini R
## Problem Title
SIH 25010: Smart Crop Advisory System for Small and Marginal Farmers
## Problem Description
A majority of small and marginal farmers in India rely on traditional knowledge, local shopkeepers, or guesswork for crop selection, pest control, and fertilizer use. They lack access to personalized, real-time advisory services that account for soil type, weather conditions, and crop history. This often leads to poor yield, excessive input costs, and environmental degradation due to overuse of chemicals. Language barriers, low digital literacy, and absence of localized tools further limit their access to modern agri-tech resources.

Impact / Why this problem needs to be solved

Helping small farmers make informed decisions can significantly increase productivity, reduce costs, and improve livelihoods. It also contributes to sustainable farming practices, food security, and environmental conservation. A smart advisory solution can empower farmers with scientific insights in their native language and reduce dependency on unreliable third-party advice.

Expected Outcomes

 A multilingual, AI-based mobile app or chatbot that provides real-time, location-specific crop advisory which helps the farmers to increase  crop yield and prevents from inorganic farming. Soil health recommendations and fertilizer guidance is also necessary to overcome this issue. It is also necessary to be aware of Weather-based alerts and predictive insights. Pest/disease detection via image uploads is a best resolution. Market price  tracking is essential. Voice support for low-literate users . Feedback and usage data collection for continuous improvement is also mandatory.

Relevant Stakeholders / Beneficiaries
                               * Small and marginal farmers
                              • Agricultural extension officers
                              • Government agriculture departments
                              • NGOs and cooperatives
                              • Agri-tech startups

Supporting Data

• 86% of Indian farmers are small or marginal (NABARD Report, 2022).
• Studies show ICT-based advisories can increase crop yield by 20–30%.

## Problem Creater's Organization
Government of Punjab

## Theme
Agriculture, FoodTech & Rural Development

## Proposed Solution
<h3>solution</h3>
AgriMitra AI is a multi-modal, hyperlocal advisory ecosystem designed for small and marginal farmers. It provides personalized, real-time farming guidance using voice, AI, AR, and offline smart devices. Unlike traditional apps, it works even in low-connectivity areas and is fully accessible to low-literate farmers, delivering advice in their native dialects.Key components include these factors ,Creates a personalized AI profile for each farmer based on soil data, crop history, irrigation patterns, and local weather.Learns from each season to improve recommendations over time.Voice-First Advisory System include, Farmers interact using voice in their local language via mobile, smart radio, or kiosk.It is Missed-call and WhatsApp integration ensures zero typing and offline usability.Offline AgriMitra Box (Smart Kiosk) represents
these factors Solar-powered, village-level device storing offline advisories, weather predictions, and crop recommendations.It Syncs data weekly to update AI models.AR-Based Crop Scanner represents Clip-on lens converts a smartphone camera into a diagnostic tool for pest and disease detection. AI + AR overlay provides visual and audio instructions.Input Bill Scanner & Fraud Detection: Farmers can scan purchase receipts from local shops.AI detects overpricing, wrong chemicals, or harmful input combinations and suggests alternatives.Gamified Reward System include Farmers earn points for following scientific advice, redeemable for inputs, discounts, or small incentives.It Encourages adoption of sustainable practices.It combines AI-powered recommendations, local language voice technology, and solar-powered offline devices to ensure that every farmer — regardless of literacy or tech access — receives tailored, trustworthy agricultural advice.


## Technical Approach
<h3>Technologies to Be Used</h3>

Frontend: React Native for cross-platform app

Backend: Python (Flask/FastAPI) + Node.js

AI/ML Models such as TensorFlow + YOLOv8 for pest/disease detection, NLP in Punjabi (via Whisper/OpenAI Whisper + Coqui), Time-series forecasting for weather + market pricingDatabase: PostgreSQL + Vector DB for AI memory are some models.Offline Support: SQLite with periodic sync + local caching.Hardware properties in Raspberry Pi for kiosks.Solar power bank integration include Smart lens accessory (low-cost design)

* Methodology and Implementation Process includes Phase 1:  Prototype & Co-Creation denotes Co-design with 2 pilot villages in Punjab. It Collect soil, crop, and pest image datasets.In Train Punjabi voice bot with dialect samples. Phase 2: Pilot Deployment includes Deploy 5–10 AgriMitra Boxes.It  distribute Smart Lenses to local FPOs.WhatsApp advisory launched with local agri officers is the best outcome.
Phase 3: Scale + Feedback Loop represent  It use farmer feedback to evolve AI Farmer Twin.It deploy in multiple districts.Partner with KVKs, NGOs, local agri shops are mandatory


## Feasibility and Viability
<h3>Feasibility</h3>
          It Works even in offline areas.It provides Low-cost hardware (~₹4,000 per kiosk) .

          WhatsApp-based solution = no app installs are one of the best methodology 

          Voice-first = inclusive of all literacy levels

Built-in analytics to monitor success

* Potential Challenges & Mitigation
Challenge	Mitigation Strategy
Low initial trust	Partner with local NGOs, extension workers
Device damage or misuse	Community ownership model + training
AI misinterpretation of dialects	Continuous model retraining from voice data
Farmer retention	Gamified rewards & local champion farmers





  
## Impact and Benefits
<h3>Social Impact</h3>

* Empowers 86% of Punjab’s small/marginal farmers

* Builds scientific thinking and confidence in decision-making

* Reduces dependence on local dealers’ misinformation

* Economic Benefits

* 20–30% yield improvement

* 15–25% reduction in input cost

* Better market timing = improved profit margins

* Environmental Benefits

* Reduced chemical misuse

* Better soil & water health

* Promotes sustainable crop cycles




  
## Research and References
<h3> Reserch and reference </h3>
NABARD All India Rural Financial Inclusion Survey (2022)

FAO: Voice-Based ICT for Farmers, 2020

“AI for Agriculture” – NITI Aayog & WEF White Paper, 2021

Studies from Punjab Agricultural University (PAU) on soil health trends

Research on gamification in low-literacy rural apps – World Bank, 2020
