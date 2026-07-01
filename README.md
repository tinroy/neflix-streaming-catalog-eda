# neflix-streaming-catalog-eda

# 🎬 Global Streaming Catalog Architecture & Longevity Audit

An end-to-end Exploratory Data Analysis (EDA) investigating the content strategy, audience distribution segmentation, ingestion velocity timelines, and structural asset decay metrics of the global Netflix streaming catalog.

## 📈 Business Objective & Summary
Streaming platforms face high customer acquisition costs and ongoing user churn variables. This project evaluates how a massive catalog handles content lifecycle stages to drive long-term viewer engagement. By parsing text parameters into continuous value structures, tokenizing genre vectors, and cross-tabulating global compliance variables, this analysis uncovers corporate acquisition trends and retention models.

## 🛠️ Tech Stack & Methods
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Statistical Frameworks:** Central Tendency & Dispersion Diagnostics ($\sigma, \sigma^2$), Joint and Conditional Probabilities, Time-Velocity Vectors, Multi-Label String Explosion.

## 🔍 Core Findings & Strategic Use Cases

### 1. Catalog Recency Skew & Data Integrity (Tier 1)
- **Data Signature:** Average title year rests near 2014, with a tightly bounded standard deviation ($\sigma \approx 8.82$ years) against a historical baseline going back to 1925.
- **Corporate Realism:** Shows aggressive recency bias. Proves production assets are prioritized for short shelf lives rather than an old evergreen base.
- **Hygiene Note:** Identified structural null matrices where `director` attributes drop out of 91% of episodic TV series due to multi-director rotation properties, highlighting data sparsity barriers for recommendation tools.

### 2. Behavioral Engineering: Volume vs. Conditional Ratio (Tier 2)
- **Data Signature:** Standing catalog volume contains 70% Movies and 30% TV Shows. 
- **The Conditional Insight:** Normalizing strictly by segment limits reveals that **43% of all TV Shows are explicitly rated for Mature Audiences (TV-MA)**, compared to only 33% of standalone movies.
- **Strategic Use Case:** High-intensity, adult-skewed plots are concentrated into episodic models. This creates regular viewing patterns, lengthening customer lifetime value (LTV) and reducing monthly recurring revenue (MRR) drops.

### 3. Pipeline Ingestion & Asset Decoloration (Tier 3)
- **Data Signature:** Inventory expansion experienced sharp exponential scaling from 2016 to 2019 (peaking at 2,016 annual additions), followed by an immediate volume deceleration through 2021.
- **Strategic Use Case:** Captures the structural switch from broad third-party catalog licensing to premium internal asset generation (*Netflix Originals*). Volume deceleration represents optimization for content equity over asset count.

### 4. CAC Arbitrage & Compliance Mandates (Tier 4)
- **Data Signature:** Row tokenization and string explosion reveal *International Movies* as the dominant standalone metadata tag.
- **Strategic Use Case:** Highlights a strategic mitigation framework against regional content restrictions (e.g., the EU's 30% local programming mandate) while leveraging global content distribution strategies—using low-cost local productions cross-border to maximize worldwide operating margins.

### 5. Longevity Funnel & Structural Cancellation (Tier 5)
- **Data Signature:** Continuous runtime distributions for feature films aggregate sharply at the physiological sweet-spot of ~95 minutes. Conversely, a crushing **67% of all episodic TV series are systematically cut after Season 1**.
- **Strategic Use Case:** Portrays aggressive portfolio management. High-risk investments are terminated early if they fail to clear target completion parameters within a 28-day window, preventing costly multi-season resource allocation.

---
*Developed as part of an Advanced Business EDA Portfolio sequence.*
