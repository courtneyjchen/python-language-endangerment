# Predicting Language Endangerment with Machine Learning
*Dislaimer: The data used in the following project is for non-commercial educational and personal use.*

## Project Overview
This project explores whether machine learning can help answer a critical question: **what makes a language endangered, and can we anticipate these patterns before it’s too late?** As languages vanish, so do unique histories, identities, and worldviews. By identifying the factors that drive endangerment, we aim to support earlier, more focused efforts to preserve linguistic and cultural diversity.

We frame the task as a multi-class classification problem, predicting a language’s level of endangerment across five categories:  
- Not Endangered  
- At Risk  
- Endangered  
- Highly Endangered  
- Extinct  

## Features  
Models are trained on socio-economic and geographic features, including:  
- Speaker counts  
- Number of countries where the language is spoken  
- Political recognition status  
- Urbanization and internet usage rates for countries where the language is spoken

## Results  
- **Baseline (majority class)**: 43% test accuracy  
- **Tuned gradient boosting & ensemble models**: ~88.3% test accuracy  

Our models demonstrated strong predictive power, with speaker population consistently emerging as the dominant driver of language vitality. By strategically grouping similar endangerment categories, we drastically improved classification stability and mitigated overfitting. The Gradient Boosting classifier and a hard voting ensemble stood out as top performers, each surpassing 88% test accuracy, underscoring the potential of machine learning to anticipate language endangerment trends.
