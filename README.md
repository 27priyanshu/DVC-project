
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
<img width="448" alt="image" src="https://github.com/27priyanshu/DVC-project/assets/95427620/50d3ed36-6a22-4130-bdf9-ee1d8d639aee">

### Plots for n_estimator = 10
<img width="960" alt="image" src="https://github.com/27priyanshu/DVC-project/assets/95427620/2dda8099-97b1-4044-9ed7-4e9a998cb0d6">

<img width="359" alt="image" src="https://github.com/27priyanshu/DVC-project/assets/95427620/ebcc15dc-ecf3-4cc6-ab16-68d19e26b99a">

<img width="549" alt="image" src="https://github.com/27priyanshu/DVC-project/assets/95427620/ee5ff811-a2de-4fa2-86c1-34a7adb61d6f">

### After changing n_estimaters to 35
<img width="444" alt="image" src="https://github.com/27priyanshu/DVC-project/assets/95427620/79262f1e-bf24-4797-b860-c636f2035818">

### Difference btw Plots of n_estimator = 10 & 35
<img width="374" alt="image" src="https://github.com/27priyanshu/DVC-project/assets/95427620/c3671ba4-fb62-46c1-ad01-aca37dc1ae61">
<img width="959" alt="image" src="https://github.com/27priyanshu/DVC-project/assets/95427620/6fa5a951-e2c7-4f85-b393-87f748583d15">
<img width="366" alt="image" src="https://github.com/27priyanshu/DVC-project/assets/95427620/cee236dd-cbe3-4bb0-a712-add6ad8a1be9">
<img width="960" alt="image" src="https://github.com/27priyanshu/DVC-project/assets/95427620/c1fc95f5-6fe4-4d33-9cf7-499abc0b7f24">



In summary, our End-to-End Machine Learning Pipeline Creation using DVC simplifies and enhances the ML development process. By leveraging DVC for data versioning and code management, we ensure reproducibility, collaboration, and efficient tracking of changes throughout the pipeline. This approach makes it easier to develop, deploy, and maintain robust ML models in real-world applications.


