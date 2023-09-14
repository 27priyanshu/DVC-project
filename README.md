
# End-to-End Machine Learning Pipeline Creation Using DVC

Machine Learning (ML) is revolutionizing industries across the globe, but the journey from raw data to a deployed ML model can be complex and challenging. To streamline this process, we introduce an **End-to-End Machine Learning Pipeline Creation using Data Version Control (DVC)**.

<img width="690" alt="image" src="https://github.com/27priyanshu/DVC-project/assets/95427620/251a635d-06d8-44a9-bdc2-29229821eb5f">


## Step 1: Data Split
In any ML project, the foundation is data. In the first step, we focus on data splitting. This involves dividing our dataset into multiple subsets, typically a training set and a testing set. By using DVC to version control our data, we ensure that the data used for training remains consistent and reproducible. DVC helps us manage large datasets efficiently, keeping track of different data versions over time.

## Step 2: Data Processing
Once we have our data, the next critical step is data preprocessing. This step involves cleaning, transforming, and preparing the data to make it suitable for training ML models. DVC comes in handy here by allowing us to version control our data preprocessing scripts and configurations. This ensures that data transformations are consistent and can be easily reproduced.

## Step 3: Training of Data
With our data prepared, we move on to training ML models. This step involves selecting an appropriate algorithm, feeding it the training data, and tuning hyperparameters. DVC can version control the code, model configurations, and model weights, allowing us to track changes made during model training. This ensures reproducibility and makes it easy to collaborate with team members or roll back to previous model versions if needed.

## Step 4: Evaluation of Data
Once the model is trained, it's crucial to evaluate its performance. We use DVC to manage evaluation metrics and validation datasets. This enables us to track model performance over time and make informed decisions about model deployment. With a clear version history, we can easily compare different model iterations and choose the best-performing one.

 
### When n_estimator = 10
<img width="588" alt="image" src="https://github.com/27priyanshu/DVC-project/assets/95427620/d2bb08a5-b4b5-4fca-95ba-ebe3e6cc3943">


### Plots for n_estimator = 10
<img width="935" alt="image" src="https://github.com/27priyanshu/DVC-project/assets/95427620/c121c87e-0236-4edc-b142-5d1460ca1338">


<img width="334" alt="image" src="https://github.com/27priyanshu/DVC-project/assets/95427620/171ce854-08f6-488c-af00-859aaede89af">


<img width="586" alt="image" src="https://github.com/27priyanshu/DVC-project/assets/95427620/0c4ec7f6-f77e-4aff-befd-db4ba74a094f">



### After changing n_estimaters to 35
<img width="589" alt="image" src="https://github.com/27priyanshu/DVC-project/assets/95427620/29ca0c57-7d74-4358-b5bc-9a700197d936">


### Plots of n_estimator = 35
<img width="939" alt="image" src="https://github.com/27priyanshu/DVC-project/assets/95427620/e710bb5d-4b59-47e6-af00-a0477d111700">

<img width="350" alt="image" src="https://github.com/27priyanshu/DVC-project/assets/95427620/9bb4e73e-63bb-45e3-abb9-18cee9a31a0e">

<img width="506" alt="image" src="https://github.com/27priyanshu/DVC-project/assets/95427620/a171ad3b-e076-4b76-81cf-8b1a1e731e4b">


In summary, our End-to-End Machine Learning Pipeline Creation using DVC simplifies and enhances the ML development process. By leveraging DVC for data versioning and code management, we ensure reproducibility, collaboration, and efficient tracking of changes throughout the pipeline. This approach makes it easier to develop, deploy, and maintain robust ML models in real-world applications.


