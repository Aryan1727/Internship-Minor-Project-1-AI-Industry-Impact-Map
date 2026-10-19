# AI Industry Impact Map
### Minor Project 1 — Artificial Intelligence
**Prepared as:** Gen AI Intern research report  
**Research date:** 19 October 2026

> **Project objective:** Map ten real-world AI applications across five industries, identify their methods and data, and evaluate business impact without overstating the evidence.

## Executive summary
AI creates business value through pattern detection, prioritization, personalization, language generation and operational optimization. This report covers healthcare, finance, retail, education and transportation. It distinguishes peer-reviewed findings, company-reported metrics, platform usage statistics and benefits that still require local validation.

## 1. Application map

### 1. Healthcare — AI-assisted chest X-ray analysis
- **AI methods:** Deep Learning / Computer Vision
- **Business problem:** Help clinicians detect and localize abnormalities in chest X-rays.
- **Data used:** Chest X-ray pixels; annotated images; clinical labels.
- **Impact / evidence:** A published evaluation reported AUC 0.976; physicians’ AUC improved by 0.101 with AI assistance. Study result, not a guaranteed hospital-wide gain.
- **Source:** [Open reference](https://pmc.ncbi.nlm.nih.gov/articles/PMC11502915/)

### 2. Healthcare — AI triage for urgent radiology scans
- **AI methods:** Machine Learning / Computer Vision
- **Business problem:** Prioritize potentially urgent scans for earlier review.
- **Data used:** CT images; model scores; scan and report timestamps.
- **Impact / evidence:** A systematic review found 67% of 33 studies measuring task time reported reductions, but pooled meta-analyses did not show significant overall effects.
- **Source:** [Open reference](https://pubmed.ncbi.nlm.nih.gov/39349815/)

### 3. Finance — Real-time payment fraud detection
- **AI methods:** Machine Learning; GenAI-enhanced scoring
- **Business problem:** Flag suspicious transactions while limiting unnecessary declines.
- **Data used:** Transaction amount/time; merchant; account/device signals; fraud outcomes.
- **Impact / evidence:** Mastercard reported a 20% average improvement in initial fraud-detection modelling; company-reported estimate, not a universal independent benchmark.
- **Source:** [Open reference](https://www.mastercard.com/in/en/news-and-trends/press/2024/february/mastercard-supercharges-consumer-protection-with-gen-ai.html)

### 4. Finance — Fraud investigation and case triage
- **AI methods:** Machine Learning / NLP
- **Business problem:** Rank suspicious cases and summarize signals to reduce manual investigation effort.
- **Data used:** Transaction histories; alerts; investigator notes; customer and merchant context.
- **Impact / evidence:** Mastercard’s research reports 83% of surveyed organizations said AI significantly sped up investigation and resolution; survey result, not a causal experiment.
- **Source:** [Open reference](https://www.mastercard.com/global/en/news-and-trends/Insights/2026/ai-is-helping-banks-save-millions-by-transforming-payment-fraud-prevention.html)

### 5. Retail — Personalized product recommendations
- **AI methods:** Machine Learning / Recommender Systems
- **Business problem:** Help customers discover relevant products and improve shopping relevance.
- **Data used:** Clicks; searches; purchases; product metadata; customer preferences.
- **Impact / evidence:** Amazon describes AI-powered personalization and recommendation improvements; the cited source does not specify a public numerical revenue lift.
- **Source:** [Open reference](https://www.aboutamazon.com/news/retail/amazon-generative-ai-product-search-results-and-descriptions)

### 6. Retail — AI-generated personalized product descriptions
- **AI methods:** Generative AI / NLP
- **Business problem:** Adapt descriptions to shopping context and highlight relevant product attributes.
- **Data used:** Product catalog text; product attributes; search and shopping activity.
- **Impact / evidence:** Potentially improves relevance and discovery; the cited source describes the capability but does not quantify a measured uplift.
- **Source:** [Open reference](https://www.aboutamazon.com/news/retail/amazon-generative-ai-product-search-results-and-descriptions)

### 7. Education — AI tutor and teaching assistant (Khanmigo)
- **AI methods:** Generative AI / NLP
- **Business problem:** Provide guided explanations and help teachers draft learning materials and feedback.
- **Data used:** Student prompts; exercise context; curriculum content; learning objectives.
- **Impact / evidence:** Khan Academy reported 2.0 million Khanmigo users during school year 2024–25. Reach is not proof of causal learning gains.
- **Source:** [Open reference](https://annualreport.khanacademy.org/)

### 8. Education — Adaptive practice and skill recommendations
- **AI methods:** Machine Learning / Predictive Analytics
- **Business problem:** Recommend practice based on learner progress and skill mastery.
- **Data used:** Answers; attempts; time on task; skill mastery; assessment results.
- **Impact / evidence:** Khan Academy reports broader platform research associating 20% learning gains with 18+ hours of practice in a school year; not attributable to GenAI alone.
- **Source:** [Open reference](https://annualreport.khanacademy.org/)

### 9. Transportation — AI-assisted autonomous driving
- **AI methods:** Deep Learning / Computer Vision / Sensor Fusion
- **Business problem:** Perceive road users, lanes and traffic signals and predict motion.
- **Data used:** Camera images; lidar/radar where used; maps; vehicle motion; labeled driving scenes.
- **Impact / evidence:** Potential value includes driver assistance and consistent perception. Performance should be assessed with transparent safety metrics; no universal savings figure is claimed.
- **Source:** [Open reference](https://www.who.int/teams/digital-health-and-innovation/harnessing-artificial-intelligence-for-health)

### 10. Transportation — Route and fleet optimization
- **AI methods:** Machine Learning / Operations Research
- **Business problem:** Plan efficient routes and dispatch schedules under time, capacity and traffic constraints.
- **Data used:** Delivery locations; road network; travel times; vehicle capacity; time windows; route outcomes.
- **Impact / evidence:** Measure miles per delivery, fuel use, on-time rate and cost per stop. A verified numerical impact was not found in the selected sources.
- **Source:** [Open reference](https://www.who.int/teams/digital-health-and-innovation/harnessing-artificial-intelligence-for-health)

## 2. Industry-wise mapping diagram
![AI Industry Impact Map](AI_Industry_Impact_Map_Diagram_Beautiful.png)

## 3. Cross-industry findings
1. **Prediction and prioritization:** valuable when data volume exceeds manual review capacity.
2. **Personalization:** uses behavioral and contextual data to tailor recommendations or practice.
3. **Generative AI:** supports language-heavy work but requires grounded content, guardrails and review.
4. **Measurement matters:** a local pilot is needed before claiming cost savings or productivity gains.
5. **Responsible deployment:** address privacy, bias, model drift, hallucination, security and overreliance.

## 4. Recommended measurement plan
- Set one primary KPI and 2–3 guardrail metrics before deployment.
- Record a pre-AI baseline; compare with a controlled or matched pilot where feasible.
- Segment outcomes to detect uneven performance.
- Track false positives/negatives, human overrides, latency, operating cost and incidents.
- Review data permissions, retention, security and model drift regularly.

## 5. Conclusion
AI can create value through prediction, personalization, automation and decision support. The business case is strongest when the workflow is well-defined, the data is reliable, impact is measurable and human accountability remains explicit. Not every application has a published, attributable financial return.

## References
- [Chest X-ray deep learning evaluation (peer-reviewed)](https://pmc.ncbi.nlm.nih.gov/articles/PMC11502915/)
- [Medical imaging workflow efficiency systematic review](https://pubmed.ncbi.nlm.nih.gov/39349815/)
- [Mastercard — GenAI for consumer protection](https://www.mastercard.com/in/en/news-and-trends/press/2024/february/mastercard-supercharges-consumer-protection-with-gen-ai.html)
- [Mastercard — AI payment fraud prevention research](https://www.mastercard.com/global/en/news-and-trends/Insights/2026/ai-is-helping-banks-save-millions-by-transforming-payment-fraud-prevention.html)
- [Amazon — Generative AI for recommendations and descriptions](https://www.aboutamazon.com/news/retail/amazon-generative-ai-product-search-results-and-descriptions)
- [Khan Academy — Annual Report SY24–25](https://annualreport.khanacademy.org/)
- [WHO — AI and health resources](https://www.who.int/teams/digital-health-and-innovation/harnessing-artificial-intelligence-for-health)

## Use AI Tool For Deep Research
- Chat GPT
- Gemini
- Deepseek
