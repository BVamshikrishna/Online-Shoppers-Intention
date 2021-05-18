# Online-Shoppers-Intention

**Problem Statement:**
People often spend a lot of time browsing through online shopping websites, but the coversion rate into purchases is low. Determine the likelihood of purchase based on the given features in the datsaset. The dataset consists of feature vectors belonging to 12,330 online sessions. The purpose of this project is to identify user behaviour patterns to effectively understand features that influence the sales.

Dataset: https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset
Data Description:

The dataset cointains the following features:

The data set provided had features which are more or less related to the purchases of the users. All features are mentioned below with explanations.

The data set provided for model making has a total entry of "12330" with "18" features. Among these features 9 features are numerical, continuous and distinct, and 9 are categorical including the target feature Revenue.

The categorical features are Special Day, Month, Operating Systems, Browser, Region, Traffic Type, Visitor Type, Weekend. The numerical features are Administrative, Administrative Duration, Informational, Information Duration, Product Related, Product Relation duration, Bounce rates, Exit rates, Page Values.

**Administrative**: Number of pages visited by the user for user account management related activities.

**Administrative Duration**: Time spent on Admin pages by the user.

**Informational**: Number of pages visited by the user about the website

**_Informational Duration**: Time spent on Informational pages by the user

**_Product Related:** Number of product related pages visited by the user

**Product Related Duration:** Time spent on Product related pages by the user.

**Bounce Rates:** Average bounce rate of the pages visited by the user. It represents the percentage of visitors who enter the site and then leave rather than continuing to view other pages within the same site.

**Exit Rates:** Average exit rate of the pages visited by the user. It is the percentage of people who left your site from that page.

**Page Values:** Average page value of the pages visited by the user. It is the average value for a page that a user visited before landing on the goal page or completing an Ecommerce transaction (or both).

**Special Day:** Closeness of the visiting day to a special event like Mother‟s Day or festivals like Christmas.

**Month:** Visiting month during the whole year.

**Operating Systems:** Operating Systems of the visitor.

**Browser:** Browser of the visitor.

**Region:** Geographic region from which the session has been started by the visitor.

**Traffic Type:** Traffic source through which user has entered the website.

**Visitor Type:** Defines the nature of user.

**Weekend:** Defines the timing of the user.


**CONCLUSION**


Dataset with outliers (without treating outliers) gave us better results.

Transformation did not improve model performance significantly.

SMOTE has improved our accuracy as the dataset was unbalanced dataset.

So, our final model is the Random Forest employed on top of SMOTE, with outliers and without transformations.

