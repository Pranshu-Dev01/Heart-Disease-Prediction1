# Heart Disease Prediction

## Description
A prediction model leveraging machine learning algorithms, such as *K-Means Clustering* and *Linear Regression*, to analyze medical data and predict the likelihood of heart disease. The project incorporates testing using *Selenium* and deployment using *Docker* and *Jenkins*.

## Steps

### Building Files
1) **train_model.py**: Contains the machine learning models.
2) **requirements.txt**: Lists the required Python libraries.
3) **heart_disease_data.csv**: The dataset used for training and testing the models.
4) **Dockerfile**: Contains the commands to containerize the application.
5) **Jenkinsfile**: Automates the integration and deployment processes.

### Git & Other Commands Used in Command Prompt
1) `mkdir <folder_name>`: Creates a folder for the project.
2) `cd <folder_name>`: Navigates to the project folder.
3) `git init`: Initializes the folder as a Git repository.
4) Add all the project files manually.
5) `git add .`: Tracks all files for version control.
6) `git commit -m "<message>"`: Commits the tracked files with a message.
7) `git remote add origin <GitHub repository link>`: Links the local repository to the remote GitHub repository.
8) `git push --set-upstream origin master`: Pushes all files to GitHub.

### Running the Application
1) Build and run the Docker container:
   ```bash
   docker build -t heart-disease-prediction .
   docker run -p 5000:5000 heart-disease-prediction
   ```
2) Execute Selenium tests:
   ```bash
   python selenium_tests.py
   ```
3) Configure Jenkins to run tests and deploy the application automatically.
