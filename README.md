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
The results of the 1st-level clustering indicated 4 clusters: "Lost Clients", "At Risk", "Can't Loose", and "Stars". Results of 2nd-level clustering recommended the breakdown of each of the four clusters into 2 sub-clusters. After analyzing genre preferences for each subcluster, we found the profile of each sub-cluster was similar in all four clusters. 






