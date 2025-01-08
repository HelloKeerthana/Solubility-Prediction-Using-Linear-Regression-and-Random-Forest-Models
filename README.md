<h1>Solubility Prediction Using Linear Regression and Random Forest Models</h1>

<p><strong>Project Overview:</strong></p>
<p>This project uses machine learning to predict the aqueous solubility (logS) of chemical compounds using the 
    <strong>Delaney Solubility with Descriptors</strong> dataset. 
    The goal is to use two machine learning models: Linear Regression (LR) and 
    Random Forest (RF) to predict solubility values and evaluate their performance.</p>

<h2>Models Used</h2>
<p>The project uses two models for prediction:</p>
<ul>
    <li><strong>Linear Regression (LR)</strong>: A simple regression model to predict solubility based on linear relationships between the features and the target variable.</li>
    <li><strong>Random Forest (RF)</strong>: An ensemble learning method that aggregates predictions from multiple decision trees to improve accuracy and capture non-linear relationships.</li>
</ul>

<h2>Evaluation</h2>
<p>The performance of both models is evaluated using:</p>
<ul>
    <li><strong>Mean Squared Error (MSE)</strong>: To evaluate how close the predicted values are to the actual solubility values.</li>
    <li><strong>R² Score</strong>: To measure how well the model explains the variance in the solubility data.</li>
</ul>

<h2>Visualization</h2>
<p>Matplotlib is used to create visualizations comparing the predictions of both models with the actual solubility values, helping to better understand how well the models are performing.</p>

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
<p>The models' performance will be displayed in the terminal after running the script. You will see the accuracy metrics including the R² score and Mean Squared Error (MSE) for both models (Linear Regression and Random Forest), as well as visualizations comparing the predicted values to actual solubility values.</p>
