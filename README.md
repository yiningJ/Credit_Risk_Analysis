# Credit_Risk_Analysis
## Overview
Through the analysis we are using 6 different models to predict credit risk for a lending services company LendingClub. Then we will be able to evaluate the performance of these models.

##Results
- Naive Random Oversampling¶
<img width="333" alt="Screenshot 2023-01-04 at 9 34 54 PM" src="https://user-images.githubusercontent.com/110696825/210688605-773e78b1-4d70-43a5-9c93-d7403b95a322.png">
<img width="700" alt="Screenshot 2023-01-04 at 9 35 13 PM" src="https://user-images.githubusercontent.com/110696825/210688631-ccdd6423-5058-477e-bcdb-112fc8fc0931.png">

- SMOTE Oversampling
<img width="343" alt="Screenshot 2023-01-04 at 9 58 38 PM" src="https://user-images.githubusercontent.com/110696825/210691407-4f94d564-5501-4210-87b8-592c966b5250.png">
<img width="716" alt="Screenshot 2023-01-04 at 9 58 55 PM" src="https://user-images.githubusercontent.com/110696825/210691452-9ce9a79d-1f41-4b62-8e02-1e85b39ce1a4.png">

- Undersampling
<img width="333" alt="Screenshot 2023-01-04 at 9 59 24 PM" src="https://user-images.githubusercontent.com/110696825/210691500-952a1d20-3740-4fe4-8fec-933fb1f1b6e1.png">
<img width="709" alt="Screenshot 2023-01-04 at 9 59 38 PM" src="https://user-images.githubusercontent.com/110696825/210691521-1b8ba425-1013-41e0-9f1a-abad615cf317.png">

- Combination (Over and Under) Sampling
<img width="341" alt="Screenshot 2023-01-04 at 10 00 07 PM" src="https://user-images.githubusercontent.com/110696825/210691574-c2c53741-8ea5-4155-a38c-03b7efe009c7.png">
<img width="709" alt="Screenshot 2023-01-04 at 10 00 26 PM" src="https://user-images.githubusercontent.com/110696825/210691607-a420841d-d3aa-4400-87bc-ef68f39b6521.png">

- Balanced Random Forest Classifier
<img width="386" alt="Screenshot 2023-01-04 at 10 01 30 PM" src="https://user-images.githubusercontent.com/110696825/210691747-2f4a7796-c856-4f9c-8cb5-03e5ad9b7ec9.png">
<img width="703" alt="Screenshot 2023-01-04 at 10 01 43 PM" src="https://user-images.githubusercontent.com/110696825/210691772-ff4caa53-0aa2-4134-8e9e-719fed2f196d.png">

- Easy Ensemble AdaBoost Classifier
<img width="377" alt="Screenshot 2023-01-04 at 10 02 10 PM" src="https://user-images.githubusercontent.com/110696825/210691816-d20fd1bf-4b5e-4b7f-9c4a-36e0b53476f5.png">
<img width="710" alt="Screenshot 2023-01-04 at 10 02 38 PM" src="https://user-images.githubusercontent.com/110696825/210691860-4614dd10-267b-40e1-bbe6-f99fcdf5d8f9.png">

##Summary
Easy Ensemble AdaBoost looks like the best model to predict credit risk as it's balanced accuvacy score is the highest at around 93% and highest recall score at 94%.
