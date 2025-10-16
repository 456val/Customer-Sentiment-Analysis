# ✈️ British Airways Passenger Sentiment Analysis

### 🧭 Project Overview  
Every review tells a story — this project explores how British Airways passengers truly feel about their flight experiences.  
By applying **Natural Language Processing (NLP)** to passenger reviews, the project classifies sentiments, uncovers emotional patterns,  
and identifies the **key causes of satisfaction and frustration**.

---

### 🎯 Purpose  
To gain actionable insights from customer feedback and understand how service quality, staff performance, and flight disruptions  
influence passenger emotions and satisfaction.

---

### 🧩 Objectives  
- Analyze sentiment polarity (positive, neutral, negative) from passenger reviews.  
- Examine how review length relates to emotional intensity.  
- Identify top words associated with positive and negative experiences.  
- Explore how interruptions (delays/cancellations) impact passenger sentiment.  
- Reveal the most common causes of delays and their emotional effects.  

---

## 📊 Insights & Findings

### 1. Sentiment Intensity Distribution  


<img width="589" height="372" alt="Sentiment Distribution" src="https://github.com/user-attachments/assets/710afa92-9f22-46ae-88c3-cbd0e5c98102" />


The histogram shows that most sentiment scores are **clustered around 0**, forming a **bell-shaped curve**.  
This indicates that most reviews are **neutral or moderately emotional**, with relatively few extreme opinions.  
The sentiment balance reflects **consistent but unremarkable performance** — passengers are neither overly delighted nor severely disappointed.  

**💡 Insight:**  
British Airways receives **steady, moderate sentiment**, suggesting service consistency but limited “wow” experiences.  

---

### 2. Review Length vs Sentiment  

<img width="622" height="453" alt="image" src="https://github.com/user-attachments/assets/8da9314b-5b0f-4cb9-a20a-aecf213bdd9f" />


**Weak Positive** and **Weak Negative** reviews have the **highest average word counts (≈145–170 words)**.  
Strongly emotional reviews (both positive and negative) are shorter, while neutral comments are concise and factual.  

**💡 Insight:**  
Moderate reviews contain **richer feedback and detailed context**, while extreme emotions drive **short, direct expressions**.  
Airlines should focus on these moderate reviews for **actionable insights**.  

---

### 3. Word Cloud Analysis  
<img width="658" height="202" alt="image" src="https://github.com/user-attachments/assets/e703bfa4-908f-438d-870d-f35aa6bda930" />


#### ✅ Positive Reviews  
Frequent words: `flight`, `service`, `seat`, `time`, `staff`, `good`, `hour`, `London`, `British Airways`.  
Emphasis on **comfort, service quality, and staff friendliness**.  
Positive mentions of **timeliness and professionalism**.  

#### ❌ Negative Reviews  
Frequent words: `delay`, `hour`, `seat`, `service`, `check`, `plane`, `Heathrow`, `business class`.  
Highlights **delays, seating discomfort, and check-in frustrations**.  
Mentions of “Heathrow” and “voucher” indicate **location-specific or compensation-related issues**.  

**💡 Insight:**  
Passengers praise **crew behavior, comfort, and punctuality**,  
but express frustration with **delays, time loss, and inconsistent service**.  

<img width="709" height="492" alt="image" src="https://github.com/user-attachments/assets/e43b67a5-9c51-4e1b-831e-808135f8ee69" />

### 4. Reviews Involving Interruptions (Cancellations & Delays)  


Sentiments range from **negative (-0.32)** to **positive (0.35)**.  
Some passengers remain neutral-to-positive even after disruptions — especially when **service recovery** is handled well.  
Strongly negative reactions occur when **communication or staff response** is poor.  

**💡 Insight:**  
Customer satisfaction during disruptions depends more on **service handling** than on the **interruption itself**.  

---

### 5. Customer Service Mentions  


Passengers acknowledge **helpful and understanding staff** with positive sentiment (~0.20).  
Poor or indifferent staff behavior drives **negative sentiment (≈ -0.32)**.  
Professional service helps **neutralize frustration** from flight delays.  

**💡 Insight:**  
Customer service is a **key emotional buffer** — it can transform a bad operational experience into a manageable one.  

---

### 6. Reviews with Specific Causes (Weather, Technical, Staffing)  


Sentiment scores remain **neutral to slightly positive (0.03–0.12)**.  
Passengers show understanding when issues stem from **weather or technical causes**.  
However, dissatisfaction grows when **communication is unclear or slow**.  

**💡 Insight:**  
Passengers forgive **uncontrollable issues (like weather)** but expect **transparency and timely updates** during disruptions.  

---

### 7. Common Causes of Delays & Cancellations  



| Cause | Mentions |
|--------|-----------|
| Crew | 154 |
| Weather | 23 |
| Technical | 15 |
| Mechanical | 5 |
| Weather Conditions | 3 |
| Maintenance | 2 |
| Technical Issues | 1 |

**💡 Insight:**  
Most delays are caused by **crew availability**, followed by **weather and technical issues**.  
Reducing crew-related delays and improving communication could significantly boost passenger sentiment.  

---

### 🧠 Summary  
This analysis reveals that British Airways maintains **service consistency**, but passengers seek **more reliability and engagement**.  
The strongest emotional responses arise from **delays, unclear communication, and inconsistent service recovery**.  
Improving **staff responsiveness, transparency, and operational punctuality** can elevate overall customer satisfaction.  


### 🛠️ Tech Stack  
- **Python** (Pandas, Matplotlib, Seaborn, NLTK, TextBlob)  
- **Natural Language Processing (NLP)**  
- **Data Visualization** (Matplotlib, Seaborn, WordCloud)  

### 📁 Dataset  
The dataset contains verified British Airways passenger reviews including review text, ratings, and sentiment classifications.
