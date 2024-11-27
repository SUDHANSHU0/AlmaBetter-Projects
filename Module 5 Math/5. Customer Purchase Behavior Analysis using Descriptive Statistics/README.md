<h1 align="center">Customer Purchase Behavior Analysis using Descriptive Statistics 📊</h1>

<style>
    h1 {
        font-size: 35px;
    }
    h1:hover {
        color: cyan;
        transition: color 0.2s ease-in-out, transform 0.2s ease-in-out;
        transform: scale(1.02);
    }
    h2 {
        font-size: 28px;
        transition: color 0.2s ease-in-out;
    }
    h2:hover {
        color: cyan;
    }
    p {
        font-size: 16px;
        line-height: 1.8;
    }
    ul li {
        font-size: 16px;
        line-height: 1.8;
        transition: color 0.2s ease-in-out;
    }
    ul li:hover {
        color: cyan;
    }
</style>

<h2>🔍 Problem Statement</h2>
<p>
    This project uses probability theory and statistical techniques to analyze customer purchasing behavior. 
    The analysis aims to identify trends, patterns, and correlations in the data to optimize marketing efforts 
    and increase offer acceptance rates.
</p>

<h2>🎯 Objective</h2>
<p>
    Analyze customer data to make informed decisions, identify spending habits, and provide actionable recommendations 
    for targeted marketing strategies.
</p>

<h2>📁 About the Dataset</h2>
<p>This dataset contains customer data from last year's marketing campaign:</p>
<ul>
    <li><b>Response:</b> ✅ 1 if the customer accepted the offer; ❌ 0 otherwise.</li>
    <li><b>ID:</b> 🆔 Unique ID of each customer.</li>
    <li><b>Year_Birth:</b> 📅 Year of birth of the customer.</li>
    <li><b>Complain:</b> ⚠️ 1 if the customer complained in the last 2 years.</li>
    <li><b>Dt_Customer:</b> 🗓️ Date of customer enrollment with the company.</li>
    <li><b>Education:</b> 🎓 Customer's level of education.</li>
    <li><b>Marital_Status:</b> 💍 Customer's marital status.</li>
    <li><b>Kidhome:</b> 👶 Number of small children in the household.</li>
    <li><b>Teenhome:</b> 🧑‍🦱 Number of teenagers in the household.</li>
    <li><b>Income:</b> 💰 Customer's yearly household income.</li>
    <li><b>MntFishProducts:</b> 🐟 Amount spent on fish products in the last 2 years.</li>
    <li><b>MntMeatProducts:</b> 🍖 Amount spent on meat products in the last 2 years.</li>
    <li><b>MntFruits:</b> 🍎 Amount spent on fruit products in the last 2 years.</li>
    <li><b>MntSweetProducts:</b> 🍬 Amount spent on sweet products in the last 2 years.</li>
    <li><b>MntWines:</b> 🍷 Amount spent on wine products in the last 2 years.</li>
    <li><b>MntGoldProds:</b> 🏆 Amount spent on gold products in the last 2 years.</li>
    <li><b>NumDealsPurchases:</b> 🛍️ Number of purchases made with a discount.</li>
    <li><b>NumCatalogPurchases:</b> 📚 Number of purchases made using catalogs.</li>
    <li><b>NumStorePurchases:</b> 🏬 Number of purchases made directly in stores.</li>
    <li><b>NumWebPurchases:</b> 💻 Number of purchases made through the company's website.</li>
    <li><b>NumWebVisitsMonth:</b> 🌐 Number of visits to the company's website in the last month.</li>
    <li><b>Recency:</b> 📆 Number of days since the last purchase.</li>
</ul>

<h2>📝 Tasks and Deliverables</h2>

<h3>✅ Task 1: Basic Clean-Up</h3>
<ul>
    <li>Handle missing values and inconsistencies in data types.</li>
    <li>Analyze the distribution of customer demographics (age, education, marital status).</li>
</ul>
<p><b>Deliverables:</b> A cleaned dataset and summary of basic statistics.</p>

<h3>📊 Task 2: Descriptive Statistics</h3>
<ul>
    <li>Calculate measures of central tendency (mean, median, mode) and measures of dispersion (variance, standard deviation).</li>
    <li>Handle outliers if necessary.</li>
</ul>
<p><b>Deliverables:</b> Detailed descriptive statistics revealing key trends in the data.</p>

<h3>🎲 Task 3: Probability Distributions</h3>
<ul>
    <li>Identify variables that follow specific probability distributions (e.g., Binomial, Normal).</li>
    <li>Calculate probabilities and expected values based on these distributions.</li>
</ul>
<p><b>Deliverables:</b> Probability distribution insights and calculated probabilities.</p>

<h3>📈 Task 4: Insights and Customer Segmentation</h3>
<ul>
    <li>Explore relationships between customer characteristics and spending habits.</li>
    <li>Segment customers based on behaviors and demographics.</li>
</ul>
<p><b>Deliverables:</b> Key insights and customer segmentation analysis.</p>

<h3>📢 Task 5: Conclusion and Recommendations</h3>
<ul>
    <li>Create clear visualizations to present findings.</li>
    <li>Use insights to make actionable recommendations for marketing strategies.</li>
</ul>
<p><b>Deliverables:</b> Visualizations and actionable recommendations based on the analysis.</p>

<h2>🚀 Getting Started</h2>
<p>To start analyzing the dataset, follow these steps:</p>

1. Clone the repository:
    ```bash
    git clone https://github.com/KushangShah/AlmaBetter-Projects.git
    cd 'Module 5 Math'/'5. Customer Purchase Behavior Analysis using Descriptive Statistics'
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

<h2>📜 License</h2>
<p>This project is licensed under the MIT License. See the <a href="https://github.com/KushangShah/AlmaBetter-Projects/blob/main/LICENSE">LICENSE</a> file for details.</p>

<h1 id="thank-you">Thank You!</h1>

<style>
    #thank-you {
        font-size: 50px;
        font-family: 'Brush Script MT', cursive;
        background: linear-gradient(to right, #ff7e5f, #feb47b);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        text-align: center;
        margin-top: 50px;
        transition: transform 0.3s ease-in-out, text-shadow 0.3s ease-in-out;
    }
    #thank-you:hover {
        transform: scale(1.1);
        text-shadow: 0 0 10px rgba(255, 126, 95, 0.8), 0 0 20px rgba(254, 180, 123, 0.8);
    }
</style>
