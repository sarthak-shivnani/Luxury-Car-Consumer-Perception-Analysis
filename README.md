# Entry Level Luxury Car Brand Analysis

## Project Overview

This project analyzes **consumer conversations** from *Edmunds forums* to gain insights into the **entry-level luxury car market of USA**.  
By analyzing the frequency and context of brand mentions, we provide strategic insights into **consumer perceptions**, **aspirational brands**, and **competitor positioning**. The analysis includes **co-occurrence matrices**, **lift calculations**, and **Multi-Dimensional Scaling (MDS)** for visualizing brand relationships.

![Car Types](images/Car-Types.png)

## Key Objectives:

- Identify **aspirational brands** based on consumer discussions.
- Understand **brand comparisons** through co-occurrence analysis.
- Calculate **lift ratios** to highlight brand associations.
- Provide **business insights** on brand positioning and competition.

---

## Business Problem

**JD Power & Associates** aims to perform a **competitive analysis** of the **entry-level luxury car market** using social media discussions.  
This analysis answers questions such as:

- **Which brand is the most aspirational?**
- **How do consumers compare brands?**
- **What are the strongest brand associations?**

---

## Analysis Pipeline

### 1. Data Collection
- Data scraped from the *Edmunds Entry-Level Luxury Performance Sedans* [forum](https://www.edmunds.com).
- Over **5000+ posts** with mentions of **various car brands** and consumer aspirations.

### 2. Data Preprocessing
- Cleaning posts: Removing noise, punctuation, and converting car models into their respective brands.
- Identifying **aspirational phrases** such as “want to,” “dream of,” and “aspire to.”

### 3. Co-occurrence Matrix
- Captures how frequently two brands are mentioned together in the same discussion.
- Highlights which brands are compared most often by consumers.

### 4. Lift Ratio Calculations
- **Lift ratios** show the strength of association between brands.
- Example: **Volkswagen and Audi** have the highest lift ratio, reflecting shared ownership.

### 5. Multi-Dimensional Scaling (MDS)
- Visualization using MDS to map how **brands are positioned** based on lift ratios.
- Example: **Mercedes and Subaru** are outliers, showing niche positions.

---

## Key Analysis Results

### 🔹 Co-occurrence Matrix:

- **BMW and Acura** are frequently compared, indicating strong competition.
- **Toyota and Honda** are often mentioned together, especially around **affordability** and **reliability**.

![Co-occurrence Matrix](images/Co-ocurance Matrix.png)

---

### 🔹 Lift Ratios:

- **Volkswagen and Audi** have the highest lift value (**3.2069**), showing strong brand association.
- **Toyota and Honda** have a lift value of **3.0502**, highlighting frequent comparisons in the **affordable car market**.

![Lift Ratios](images/Lift Ratios.png)

---

### 🔹 MDS Plot:

- **Audi, BMW, Lexus, Infiniti, and Acura** cluster closely, indicating frequent consumer comparisons in the **luxury market**.
- **Mercedes and Subaru** are far from other brands, reflecting their **distinct market positions**.

![MDS Plot](images/MDS-PLOT.png)

---

## Business Insights

### 🔹 Toyota as the Most Aspirational Brand
- **Insight:** Toyota frequently appears in discussions with **aspirational phrases**, driven by its reputation for **reliability** and **hybrid technology**.
- **Recommendation:** Highlight leadership in **green technologies** and **sustainability**.

### 🔹 BMW vs. Acura – Strong Comparisons
- **Insight:** BMW and Acura are heavily compared in the **entry-level luxury market**.
- **Recommendation:** BMW can emphasize **performance**, while Acura highlights its **affordable luxury** appeal.

### 🔹 Volkswagen and Audi – Cross-Brand Marketing
- **Insight:** These brands are often mentioned together due to **shared ownership**.
- **Recommendation:** Highlight **Volkswagen’s affordability** and **Audi’s premium features** in marketing.

### 🔹 Subaru's Niche Positioning
- **Insight:** Subaru is infrequently compared, reflecting a **rugged, adventure-oriented** brand image.
- **Recommendation:** Continue targeting **outdoor enthusiasts** and emphasize **all-wheel-drive models**.

---

## Conclusion

This project provides valuable insights into the **entry-level luxury car market**, helping brands like **Toyota, BMW, Audi**, and **Acura** understand their **market positioning**, **consumer comparisons**, and **aspirational appeal**.  
These insights can inform **marketing strategies**, **brand differentiation**, and **customer engagement**.

---

## Tech Stack

- **Python**
- **Pandas** for data manipulation
- **Matplotlib** for visualizations
- **scikit-learn** for MDS plotting
- **BeautifulSoup** for web scraping
