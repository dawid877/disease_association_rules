## Association Rules on Diseases Dataset

The goal of this project was to explore frequent combinations of health-related behaviors and symptoms in the context of asthma.  
The dataset includes respiratory symptoms, geographic features, and lifestyle habits. A small portion of individuals in the dataset are diagnosed with asthma.  

Using **association rules**, I compared asthmatic and non-asthmatic groups to uncover distinguishing patterns of behavior and symptoms.

## Tech Stack
- **Language:** R  
- **Packages:** `arules`, `arulesViz`

## Project Structure
- `Association_rules.ipynb` — Core R notebook  
- `Association_Rules_disease.html` — HTML version of the notebook  
- `asthma_disease_Data.csv` — Dataset used in the analysis  
  > This file must be in the same directory when running `Association_rules.ipynb`


## Key Insights

 Asthmatic individuals differ most notably from non-asthmatics in respiratory symptoms. Wheezing is reported by 65.3% of asthmatics compared to 59.3% of non-asthmatics, while nighttime symptoms are significantly higher in asthmatics (55.6% vs. 39.5%). 
Chest tightness and shortness of breath show smaller differences between groups.

Lung function measures also set asthmatics apart. While 45.2% have high FVC, 27.4% have low FVC, compared to 44.7% and 33% in non-asthmatics, suggesting more variability in lung function among asthmatics.

Environmental factors such as pollution and pollen exposure are similar between groups, with only slight differences in high exposure levels (43.5% vs. ~41%). Asthmatics also remain just as physically active as non-asthmatics, though they report slightly better sleep quality.

Notably, asthmatics are less likely to smoke (11.3% vs. 14.3%) and have slightly lower rates of pet allergies, eczema, and hay fever, contradicting common assumptions. A family history of asthma appears equally in both groups (30%), reinforcing its genetic influence.

Overall, asthma is best distinguished by respiratory symptoms and lung function, while lifestyle and environmental factors show only minor differences
