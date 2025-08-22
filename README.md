# Predicting Language Endangerment with Machine Learning
*Dislaimer: The data used in the following project is for non-commercial educational and personal use.*

## Project Overview
This project explores whether machine learning can help answer a critical question: **what makes a language endangered, and can we anticipate these patterns before it’s too late?** As languages vanish, so do unique histories, identities, and worldviews. By identifying the factors that drive endangerment, we aim to support earlier, more focused efforts to preserve linguistic and cultural diversity. We built five models—a baseline, Gradient Boosting, ensemble, Extra Trees, and neural networks—to explore their ability to predict levels of language endangerment and uncover the features most strongly linked to linguistic survival.

The model classifies each language into one of five endangerment levels:
- Not Endangered
- At Risk
- Endangered
- Highly Endangered
- Extinct

Models are trained on socio-economic and geographic features, including:  
- Speaker counts  
- Number of countries where the language is spoken  
- Political recognition status  
- Urbanization and internet usage rates in countries where the language is spoken

## Results  
- **Baseline (majority class)**: 43% test accuracy  
- **Tuned gradient boosting & ensemble models**: ~88.3% test accuracy

Ultimately, all models demonstrated strong predictive power, with speaker population consistently emerging as the most influential factor of language vitality. By strategically grouping similar endangerment categories, we drastically improved classification stability and mitigated overfitting. The Gradient Boosting classifier and a hard voting ensemble stood out as top performers, each surpassing 88% test accuracy, underscoring the potential of machine learning to anticipate language endangerment trends.

## Final Deliverable
📌 For the complete narrative and final results, please see our final [report](https://github.com/courtneyjchen/python-language-endangerment/blob/main/output/Predicting%20Language%20Endangerment%20-%20Report.pdf) and [presentation](https://github.com/courtneyjchen/python-language-endangerment/blob/main/output/Predicting%20Language%20Endangerment%20-%20Deck.pdf). These documents showcase our approach and synthesize the analysis into a clear, compelling format.

**Contributors:** Jordan Andersen, Brian Woods, Helin Yilmaz
