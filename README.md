<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Solubility Prediction Model</title>
</head>
<body>

    <h1>Solubility Prediction Using Linear Regression and Random Forest Models</h1>
    
    <p><strong>Project Overview:</strong></p>
    <p>This project uses machine learning to predict the aqueous solubility (logS) of chemical compounds. The dataset contains molecular descriptors that describe the physical and chemical properties of compounds, and the task is to predict their solubility in water using two regression models:</p>

    <ul>
        <li><strong>Linear Regression</strong>: A simple, interpretable model that assumes a linear relationship between the features and the target variable.</li>
        <li><strong>Random Forest Regression</strong>: An ensemble learning method that uses multiple decision trees to improve prediction accuracy, capturing non-linear relationships.</li>
    </ul>

    <h2>Dataset</h2>
    <p>The dataset used in this project is <strong>Delaney Solubility with Descriptors</strong>, which includes several molecular descriptors such as:</p>
    <ul>
        <li>Molecular Weight (MW)</li>
        <li>LogP (Octanol-water partition coefficient)</li>
        <li>Number of Rotatable Bonds</li>
        <li>Number of Hydrogen Bond Donors (HBD)</li>
        <li>Number of Hydrogen Bond Acceptors (HBA)</li>
        <li>Topological Polar Surface Area (TPSA)</li>
    </ul>

    <h2>Objective</h2>
    <p>The main goal of this project is to predict the solubility of chemical compounds based on the given molecular descriptors and evaluate the performance of the models in terms of accuracy and interpretability.</p>

    <h2>Model Evaluation</h2>
    <p>The models are evaluated based on:</p>
    <ul>
        <li><strong>Mean Squared Error (MSE)</strong>: Measures the average squared difference between the actual and predicted values.</li>
        <li><strong>R² Score</strong>: A measure of how well the model explains the variance in the target variable.</li>
    </ul>

    <h2>Installation</h2>
    <p>To run this project locally, follow these steps:</p>
    <pre>
# Clone the repository
git clone <your-repository-url>

# Install necessary dependencies
pip install -r requirements.txt
    </pre>

    <h2>Usage</h2>
    <p>To train and evaluate the models, run the following Python script:</p>
    <pre>
python solubility_prediction.py
    </pre>

    <h2>Results</h2>
    <p>The models' performance is displayed in the terminal after running the script. You will see the accuracy metrics including the R² score and Mean Squared Error (MSE) for both models (Linear Regression and Random Forest).</p>

    <h2>License</h2>
    <p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>

</body>
</html>
