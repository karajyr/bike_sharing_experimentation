# bike_sharing_analysis

Tools used: Python (scikit-learn, statsmodels, Pandas, NumPy, SciPy, matplotlib/Seaborn)

Main methods used: exploratory data analysis, multiple hypothesis testing correction for A/B testing, Gaussian Mixture Models (GMMs), causal inference (instrumental variables with 2SLS)

The main goals of this project were to use various statistical methods to: 

(1) visualize and produce descriptive statistics of rider demographics, rental times, and popular biking routes 

(2) perform A/B test given null hypothesis that rider is not a subscriber (i.e. a causal rider) and used Benjamini-Hochberg algorithm to correct false discovery rate; improve average sensitivity with additional covariates

(3) model subscriber or casual (non-subscriber) riders distributions within each city's bike share dataset using GMMs and create classifier using posterior probabilities of subscribers

(4) establish a causal relationship between weather condition and number of bike rentals 
