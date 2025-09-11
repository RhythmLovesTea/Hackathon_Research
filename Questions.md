## 1. Why is this problem important now?
**Answer:**  
- Over 27,000 tracked objects and millions of untracked fragments threaten satellites.  
- With mega-constellations (Starlink, OneWeb), congestion risk is rising fast.  
- If we don’t build collaborative tools now, space traffic will be as chaotic as unregulated air traffic.  

---

## 2. Aren’t NASA, ESA, ISRO already solving this? Why do we need you?
**Answer:**  
- They track but don’t share openly — data stays in silos due to security/political issues.  
- Our platform is not about new tracking, but about making existing data accessible, intuitive, and neutral.  
- Think of us as the **“Google Maps” layer** — not building satellites, but making space traffic visible to everyone.  

---

## 3. How will you get data if agencies don’t share?
**Answer:**  
- Many open datasets exist (e.g., **CelesTrak**, **Space-Track.org**).  
- We start with public TLEs → convert them into interactive, user-friendly visuals.  
- Over time, we can add commercial partnerships or crowdsourced telescope data.  

---

## 4. Who is the end-user? Who benefits most?
**Answer:**  
- **Policymakers** → understand congestion before approving launches.  
- **Startups** → plan safe orbits without needing an aerospace PhD.  
- **Researchers & Educators** → easier access for academic projects.  
- **General Public/Students** → space awareness, STEM learning.  

---

## 5. How is your solution different from existing visualization tools?
**Answer:**  
- Existing tools are often too technical, closed-source, or restricted.  
- We focus on **neutrality, accessibility, and simplicity** — not just for engineers, but for decision-makers.  
- Current dashboards = “for scientists only.”  
- Ours = “anyone can see orbital traffic, understand congestion, and collaborate.”  

---

## 6. What about trust? Why will agencies or companies trust your dashboard?
**Answer:**  
- Neutral, open-source foundation builds transparency.  
- Instead of replacing agencies, we aggregate & visualize what is already public.  
- Over time, partnerships can grow as we prove neutrality (like Linux did in software).  

---

## 7. How do you plan to scale beyond a hackathon prototype?
**Answer:**  
- **Phase 1:** Hackathon → interactive demo using TLE data.  
- **Phase 2:** Expand datasets (commercial + research).  
- **Phase 3:** Add features like collision alerts, congestion heatmaps, API access.  
- **Long-term:** Become the global “common operating picture” for space traffic.  

---

## 8. What technologies will you use to build this prototype?
**Answer (tech-friendly):**  
- **Frontend:** React + CesiumJS (3D Earth visualization).  
- **Backend:** Node.js / Python for parsing orbital data.  
- **Database:** PostgreSQL for storing objects & metadata.  
- **Data Source:** TLE datasets (CelesTrak / Space-Track).  

---

## 9. What makes your solution innovative?
**Answer:**  
- Not another tracking radar.  
- We solve **fragmentation, accessibility, and trust gap** — which nobody is tackling in a user-friendly way.  
- It’s like taking raw GPS satellite data → turning it into **Google Maps**.  

---

## 10. What’s your biggest challenge?
**Answer:**  
- **Data trust & adoption.** Agencies may be slow to share.  
- But even if only public datasets are used, our tool still adds value by making it **visual, intuitive, and collaborative**.  

---

## ❓ 1. Judge: “Where will you get your data if you’re not using military satellites?”
**👉 Answer:**  
“We use publicly available datasets like CelesTrak and Space-Track.org, which are updated daily. These cover debris, defunct satellites, and commercial constellations — more than enough to demonstrate orbital congestion.”  

---

## ❓ 2. Judge: “Aren’t you missing critical accuracy by avoiding military data?”
**👉 Answer:**  
“Military accuracy is not our goal. Our focus is awareness and accessibility for commercial, policy, and educational users. Even with public data, we can clearly show traffic density, risks, and collision scenarios.”  

---

## ❓ 3. Judge: “Why focus on commercial satellites like Starlink or OneWeb?”
**👉 Answer:**  
“Because mega-constellations are the fastest growing source of congestion in LEO. They are commercial, not classified, and directly impact collision risk, making them the most relevant case for policymakers and startups.”  

---

## ❓ 4. Judge: “How will your tool help policymakers or educators, not just engineers?”
**👉 Answer:**  
“Our dashboard simplifies raw orbital data into maps, density visuals, and traffic flows. A policymaker can instantly see congestion zones, while students can learn orbital dynamics in an intuitive way.”  

---

## ❓ 5. Judge: “If agencies already publish data, what’s new in your solution?”
**👉 Answer:**  
“Agencies publish raw files like TLEs, which are technical and inaccessible to most. Our innovation is turning that data into a Google-Maps-like dashboard that is neutral, intuitive, and collaborative.”  

---

## ❓ 6. Judge: “Couldn’t your dashboard be misused if made public?”
**👉 Answer:**  
“No — we only show public data that’s already available, but in a clearer format. Military or classified objects are excluded, so the platform remains safe while still promoting awareness.”  

---

## ❓ 7. Judge: “What’s the biggest value even without military data?”
**👉 Answer:**  
“Even without military data, we show the majority of real traffic — commercial satellites and debris. That’s enough to highlight congestion risks, demonstrate collision possibilities, and support safer decision-making.”  

---

## 🔑 Core One-Liner (for repeated pushbacks on military data)
**👉 Memorize this line:**  
“Our focus is not military precision — it’s accessibility and awareness. By using only public data, we stay safe, legal, and still demonstrate congestion clearly enough for policymakers, startups, and students.”

---

## ❓ 1. Judge: “Your dashboard has both public and agency modes. How will you ensure sensitive data isn’t leaked?”
**👉 Answer:**  
“We implement role-based access control. Public users see simplified orbital density and educational visuals, while agencies log in securely to access high-accuracy data. Sensitive or military data is never ingested or exposed.”  

---

## ❓ 2. Judge: “What exactly makes your public dashboard valuable if agencies already track?”
**👉 Answer:**  
“Agencies track, but their data is raw and technical. Our public dashboard makes it intuitive — interactive maps, heatmaps, animations — so students, researchers, startups, and policymakers can understand orbital congestion at a glance.”  

---

## ❓ 3. Judge: “Collision prediction is very complex — can you really do that in a hackathon?”
**👉 Answer:**  
“For the hackathon, we’ll implement a simplified conjunction demo using open TLE data and libraries like sgp4. Advanced AI-based forecasting is a stretch goal beyond the hackathon.”  

---

## ❓ 4. Judge: “AI risk forecasting sounds ambitious. How realistic is that?”
**👉 Answer:**  
“Absolutely, it’s ambitious. Our approach is modular — the hackathon prototype focuses on visualization. AI forecasting modules can be plugged in later, enabling researchers and startups to experiment with it.”  

---

## ❓ 5. Judge: “Why heatmaps and animations? Isn’t that oversimplifying orbital mechanics?”
**👉 Answer:**  
“Our aim is not to replace scientific analysis, but to increase accessibility. Heatmaps and animations translate math-heavy orbital mechanics into insights that non-specialists can understand.”  

---

## ❓ 6. Judge: “How will agencies trust your platform with their data?”
**👉 Answer:**  
“We propose a federated data-sharing model — agencies upload anonymized or aggregated data through encrypted channels. We don’t store sensitive details, we just enable secure collaboration.”  

---

## ❓ 7. Judge: “Which technologies are you using to implement this and why?”
**👉 Answer:**  
- **CesiumJS** for 3D globe visualization (best fit for satellites).  
- **sgp4/Skyfield** for orbit propagation.  
- **FastAPI backend** to serve JSON orbital data.  
- **PostgreSQL** for storing history & queries.  
- **React frontend** for interactivity.  

👉 Together, these tools allow us to move from raw TLEs → clean visuals quickly.  

---

## ❓ 8. Judge: “Why not just use ESA or NASA’s existing dashboards?”
**👉 Answer:**  
“ESA and NASA dashboards are closed, highly technical, and not built for collaboration. Our platform is neutral, open-source, and layered — designed for policymakers, startups, and educators too, not just scientists.”  

---

## ❓ 9. Judge: “How will you scale beyond the hackathon prototype?”
**👉 Answer:**  
- **Prototype →** interactive visualization from public data.  
- **Next →** add density analytics, collision alerts, role-based logins.  
- **Later →** extend to AI forecasting, orbit optimization, and debris removal simulations.  

The design is modular, so it scales step by step.  

---

## ❓ 10. Judge: “What’s your strategic value if this already exists in parts?”
**👉 Answer:**  
“Our unique value is integration + accessibility. Existing tools are siloed and expert-only. We bridge the gap by offering a unified, collaborative, and intuitive dashboard that empowers a wider audience.”
