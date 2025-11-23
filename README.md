<img width="1405" height="786" alt="image" src="https://github.com/user-attachments/assets/d22b5358-415e-4f7d-ab25-922b14ad2e97" />
# 👗 Sustainable Fashion Marketplace — End-to-End Data Analysis Project  
### **Author: Vera Malavolti**  
*Final Project — Master in Data Analysis*

## 📚 Project Overview  
This project provides a complete analytical workflow on a **second-hand fashion marketplace dataset**, transforming raw transactional data into **strategic insights** through SQL, Python and Tableau.  
The analysis highlights sales trends, user clusters, high-impact product categories, and platform performances, enabling data-driven decisions to optimize product quality, user retention, and marketplace growth.

The full presentation with visual insights is available in the project PDF.  
*(“Sustainable Fashion: Data Analysis of a Second-Hand Clothing Marketplace”)* :contentReference[oaicite:0]{index=0}


<img width="1405" height="786" alt="image" src="https://github.com/user-attachments/assets/ca90ba6a-0a8e-46b7-a6db-9f0dc2df1f16" />
## 🧠 Objectives  
- Analyze **temporal trends** in sales  
- Identify **seller clusters** and understand their behavior  
- Determine which **categories and designers** drive the marketplace  
- Compare performance across **platforms and price levels**  
- Provide **strategic recommendations** for next year’s roadmap

## 🧰 Tools & Technologies  
- **SQL (SQLite)** — data cleaning, preparation, aggregated views  
- **Python** — Pandas, NumPy, Matplotlib, Seaborn  
- **Tableau** — dashboards and visual storytelling  
- **Jupyter Notebook** — full EDA workflow  
  
<img width="1405" height="786" alt="image" src="https://github.com/user-attachments/assets/b6015336-c8b5-40cd-a177-b56e8fa10b85" />
## 📦 Dataset Description  
The dataset includes detailed attributes for each sale, such as:  
- Product category & designer  
- Price level (budget • mid • premium)  
- User characteristics (country, language, subscription date, activity level)  
- Average product rating  
- Device/platform of the transaction  
- Purchase date  
- Unique seller and product identifiers  

*(Dataset structure shown in PDF, p.3)* :contentReference[oaicite:1]{index=1}

<img width="1405" height="786" alt="image" src="https://github.com/user-attachments/assets/f65dade2-05da-40ac-a1df-8e854b7bcd47" />
## **Dataset Structure and Features**
The dataset contains all transactions completed by sellers on a second-hand fashion marketplace.  
Each row corresponds to a single sale and includes details on products, users, and context.  
:contentReference[oaicite:2]{index=2}

### **Main Variables Included**
- `purchase_date` — date of transaction  
- `user_uuid` — unique seller ID  
- `category` — product type (e.g., dress, shoes, jacket)  
- `designer_id` — brand / designer  
- `language` — seller’s language  
- `level` — price range (budget, mid, premium)  
- `country` — seller’s country  
- `subscription_date` — registration date  
- `device/platform` — mobile, desktop, app…  
- `stars` — average product rating  
- `sale_id` — unique transaction identifier  

These attributes enabled a multi-layer analysis on:
- seller behavior  
- product performance  
- country/language trends  
- price positioning  
- customer satisfaction  


<img width="1405" height="786" alt="image" src="https://github.com/user-attachments/assets/4d6c518a-8e19-4d5b-aa40-16920e631cd5" />
## **Analytical Pipeline**
The project follows a structured workflow (Slide 4):  
:contentReference[oaicite:3]{index=3}

### **🔹 SQL**
Used to clean and structure the raw dataset into a relational database, generating aggregated views such as:
- monthly sales  
- user-level summaries  
- category and device performance  

### **🔹 Python**
Used for:
- data cleaning & preprocessing  
- exploratory data analysis (EDA)  
- feature engineering  
- identifying correlations  
- preparing data for clustering & visualization  

### **🔹 Tableau**
Used for:
- interactive dashboards  
- strategic storytelling  
- visual communication of patterns  

This multi-tool approach ensures a complete journey from raw data to strategic insights.


<img width="1405" height="786" alt="image" src="https://github.com/user-attachments/assets/346e5f5f-0976-4d62-b9c9-e94c3be7697a" />

<img width="1405" height="786" alt="image" src="https://github.com/user-attachments/assets/da1624da-f71a-4d99-80db-59a0f68dff90" />

<img width="1405" height="786" alt="image" src="https://github.com/user-attachments/assets/c16caf4a-bfc2-4512-af69-301397319237" />
## **Seller Clusters & Behavior Patterns**
The user base was segmented into three personas using behavioral indicators:  
:contentReference[oaicite:4]{index=4}

### **1️⃣ Jenny Humphrey — The Mass Sellers**
- Represent **~40%** of all users  
- High volume of sales  
- Low average rating (**≈2.9**)  
- Tend to sell lower-value products  
➡️ *Risk*: pulling the platform’s quality perception downward  

### **2️⃣ Blair Waldorf — The Balanced Performers**
- About **42%** of sellers  
- Consistent performance (≈5 sales/user)  
- Above-average rating (**≈3.2**)  
➡️ *Backbone of the marketplace*: reliable, profitable sellers  

### **3️⃣ Serena van der Woodsen — The Premium Group**
- Only **18%**, but with highest rating (**≈3.3**)  
- Regular, trusted sellers  
➡️ *Small but strategic*: high customer satisfaction, stable performance  

### **Strategic Actions (Slide 7)**
- **Empower Blair** → loyalty programs, exclusive benefits  
- **Support Serena** → visibility, “quality badge” features  
- **Improve Jenny** → training, commission discounts, better product presentation  

<img width="1405" height="786" alt="image" src="https://github.com/user-attachments/assets/e4aa68d5-4cef-4c54-a6ca-e2ccb7862a98" />
## **Temporal Trend Analysis**
Slide 9 reveals the evolution of sales over time.  
:contentReference[oaicite:5]{index=5}

### **Key Findings**
- Sales show **steady and consistent growth**, especially from early 2022.  
- Growth is driven primarily by the **premium segment**, which increases month after month.  
- **Budget** and **mid** segments fluctuate more, but provide essential baseline volume.  
- The platform is shifting toward a **value-driven model** with more premium transactions.  

<img width="1405" height="786" alt="image" src="https://github.com/user-attachments/assets/ab3eff8d-3e17-4093-9057-f05f095f7133" />
## **Category Performance**
Not all product categories contribute equally to marketplace success.  
:contentReference[oaicite:6]{index=6}

### **Top Performing Categories**
- **Belts** — highest volume + excellent ratings  
- **Shoes**  
- **Bottoms**

These categories generate most of the platform’s traffic and revenue.

### **Underperforming Categories**
- **Shirts**  
- **Activewear**

Lower sales volume + weaker ratings → require strategic improvement:
- better photography  
- richer descriptions  
- targeted promotions  

### **Balanced Categories**
- **Dresses**  
- **Bottoms**

Useful for diversifying the marketplace offer and attracting different audience segments.

<img width="1405" height="786" alt="image" src="https://github.com/user-attachments/assets/e06f0d6f-d202-430e-9f7f-c405c5f3cece" />

<img width="1405" height="786" alt="image" src="https://github.com/user-attachments/assets/9cdce801-1e86-4c2e-90c2-3899303ec279" />

<img width="1405" height="786" alt="image" src="https://github.com/user-attachments/assets/af883959-63bc-4476-8516-3b62e2273937" />

<img width="1405" height="786" alt="image" src="https://github.com/user-attachments/assets/5f0b2315-ceb2-4b78-8f69-9eed13ae1e3a" />
