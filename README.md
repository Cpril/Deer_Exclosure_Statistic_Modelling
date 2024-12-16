# Oh Deer! Impact of Deer on Forest Ecosystem
![DeerExclosurePicture](https://github.com/user-attachments/assets/3acb7243-f410-48be-9b26-15fc085fa846)
Figure 1: Plant Diversity Measurement being taken in a deer exclosure
### Introduction & Research Question
We are tasked by Matt Dystra, director of Calvin University Ecosystem Preserve, to analyze data for Pierce Cedar Creek Institute and attempt to answer the following research question: 
**How does deer presence affect plant diversity, controlling for possible effects of season and location?**

### Exploritory Data Analysis: 
![image](https://github.com/user-attachments/assets/f0b6efbd-1883-45a2-98e1-5718bf4751fc)
Figure 2: Plant Diversity (shannon-Wenner diversity measure) by site and season. 

![image](https://github.com/user-attachments/assets/da3d8488-6aaa-4ea4-921e-37f56bad7714)
Figure 3: Richness (Number of Species) by Site and Season. 

### Prediction Plot:
![image](https://github.com/user-attachments/assets/0d6700a1-9111-4815-8047-33f0fbd0f67f)
Figure 4: Prediction Plot of Plant Diversity by Site show large variation between site and conflicting direction of fencing impact.

### Conclusion: 
Our model passes all assessment conditions, including independence and normality of residuals, constant variance, and lack of non-linearity.

There is very strong evidence (p < 0.0001) suggesting that fencing and site interacts and affect plant diversity. The direction of this effect is ambiguous. Based on prediction plot, we find that fencing is associated with decreased plant diversity for site West and North, and has little effects for site Creek and South.

### Future Direction: 
Future investigation could control for the initial diversity present in each site, which could further isolate the effect of fencing. Other opportunities for future analysis would be using richness as the response variable instead of diversity, or some exploration of individual species of interest.

### Acknowledgement
Data gathered by Matt Dystra and data science project recieved guidance from Professor Stacy DeRuiter at Calvin University. 
