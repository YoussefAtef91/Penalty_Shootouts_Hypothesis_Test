# **Penalty Shootout Hypothesis Test**  

## **Overview**  
This project investigates whether the team that starts a penalty shootout in soccer has an advantage. Inspired by a commentator’s remark during an FA Cup match, I conducted a **hypothesis test** to determine if the first-shooting team wins significantly more often than expected by chance.  

## **Hypothesis**  
- **Null Hypothesis (H₀):** The probability of the first team winning is **50%** (*no advantage*).  
- **Alternative Hypothesis (Hₐ):** The probability of the first team winning is **not 50%** (*potential advantage or disadvantage*).  
- **Test Type:** Two-tailed **z-test for one group**  

## **Methodology**  
### **1. Power Analysis**  
To determine the minimum sample size required, I performed a **power analysis** using:  
- **Effect size** = 0.1 (Cohen’s *h*)  
- **Significance level (α)** = 0.05  
- **Power** = 80%  

This analysis determined that **at least 197 matches** were needed for statistical validity.  

### **2. Data Collection**  
I scraped data from **Transfermarkt**, focusing on penalty shootout matches played on **neutral ground** to eliminate home-field bias.  
- **Competitions included (full dataset):**  
  - FIFA World Cup, Club World Cup, AFCON, Copa América, AFC Asian Cup, Community Shield, and the Olympics.  
- **Competitions included (finals only):**  
  - UEFA Champions League, UEFA Europa League, FA Cup.  

Assumption: Since both teams reached a penalty shootout, we assume they had comparable form on the match day.  

### **3. Hypothesis Testing**  
- Calculated the proportion of wins for the first-shooting team.  
- Performed a **z-test** for a **one-group** two-tailed test.  
- Compared the **p-value** with the **significance level (0.05)**.  

## **Results & Conclusion**  
- The first team won **55%** of the time.  
- The **z-test p-value** = **0.097** (*greater than 0.05*).  
- Since **p > 0.05**, we **fail to reject** the null hypothesis.  

### **Final Conclusion:**  
We **cannot conclude** that the first-shooting team has an **advantage** (or disadvantage). The difference observed is **not statistically significant**.  

## **Contact**  
If you have any suggestions or feedback, feel free to reach out! 🚀  
