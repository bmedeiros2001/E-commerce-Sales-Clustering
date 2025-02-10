# E-commerce-Sales-Clustering

## Project Summary:
Performed two-level k-means clustering on data for a book e-commerce website.

- 1st-level clustering was based on RFM ("recency", "frequency" and "monetary") and "tof"
- 2nd-level clusteringg was based on the 30 frequency columns for all genres

---

## Dataset Information:
- One row for each client.

**Columns:**
- recency (days since last purchase)
- frequency (total number of times client made a purchase on the website)
- monetary (total money client spent on website)
- time on file ("tof") (number of days client has name on file)
- 30 columns on frequency of purchase for each genre) (ex: "Flearning37", "Fhealth35")
- 30 columns on total monetary value spent for each genre) (ex: "Mlearning37", "Mhealth35")

---

## Results
**The results of the 1st-level clustering indicated 4 clusters:** "Lost Clients", "At Risk", "Can't Loose", and "Stars". 

<p align="center">
  <img width="700" alt="Image" src="https://github.com/user-attachments/assets/a88463d5-996e-4095-9bd3-e41708f7180a" />
</p>

**Results of 2nd-level clustering recommended that each of the four clusters be broken into 2 sub-clusters.** After analyzing genre preferences for each subcluster, we found the profile of each sub-cluster was similar in all four clusters. 

<p align="center">
  <img width="700" alt="Image" src="https://github.com/user-attachments/assets/ba1b7509-6319-4706-81d0-e74de628560a" />
</p>

**Simplified final structure:**

<p align="center">
  <img width="900" alt="Image" src="https://github.com/user-attachments/assets/7dd5853b-8556-4572-9292-06757e62a39d" />
</p>

---

## Disclaimers and Additional Information
- This final project is for a data science consulting class that presents case studies simulating real-world business challenges. Students apply machine learning techniques while ensuring insights are clear and support decision-making. The final presentation introduces a fictional consulting firm, representing the class team and their previous projects.
- Beyond clustering analysis, the team proposed a marketing strategy for the e-commerce company, including revenue growth projections.






