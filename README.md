<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Customer Retention & Dynamic Pricing Analysis</title>

    <style>
        body{
            font-family: Arial, Helvetica, sans-serif;
            margin:0;
            padding:0;
            background:#0f172a;
            color:#f1f5f9;
            line-height:1.7;
        }

        header{
            background:linear-gradient(135deg,#0ea5e9,#7c3aed);
            padding:60px 20px;
            text-align:center;
        }

        header h1{
            font-size:48px;
            margin-bottom:10px;
        }

        header p{
            font-size:20px;
        }

        .container{
            width:90%;
            max-width:1200px;
            margin:auto;
            padding:40px 0;
        }

        section{
            background:#1e293b;
            margin-bottom:30px;
            padding:30px;
            border-radius:12px;
            box-shadow:0 4px 15px rgba(0,0,0,0.3);
        }

        h2{
            color:#38bdf8;
            border-bottom:2px solid #334155;
            padding-bottom:10px;
            margin-bottom:20px;
        }

        h3{
            color:#a78bfa;
            margin-top:25px;
        }

        ul{
            padding-left:20px;
        }

        table{
            width:100%;
            border-collapse:collapse;
            margin-top:20px;
        }

        table th,
        table td{
            border:1px solid #334155;
            padding:12px;
            text-align:left;
        }

        table th{
            background:#334155;
            color:#38bdf8;
        }

        code{
            background:#0f172a;
            color:#38bdf8;
            padding:3px 6px;
            border-radius:5px;
        }

        pre{
            background:#0f172a;
            padding:20px;
            overflow-x:auto;
            border-radius:10px;
        }

        .highlight{
            color:#22c55e;
            font-weight:bold;
        }

        .dashboard{
            margin-top:20px;
            text-align:center;
        }

        .dashboard img{
            width:100%;
            border-radius:12px;
            margin-top:15px;
            border:2px solid #334155;
        }

        footer{
            background:#020617;
            text-align:center;
            padding:20px;
            color:#94a3b8;
        }
    </style>
</head>

<body>

<header>
    <h1>🏨 Customer Retention & Dynamic Pricing Analysis</h1>
    <p>Hospitality Analytics | Machine Learning | Business Intelligence</p>
</header>

<div class="container">

    <section>
        <h2>📌 Project Overview</h2>

        <p>
            The hospitality industry faces significant revenue loss due to customer cancellations,
            poor demand forecasting, and inefficient pricing strategies.
        </p>

        <p>
            This project analyzes hotel booking data using 
            <span class="highlight">Python, Machine Learning, EDA, and Power BI</span>
            to identify cancellation patterns, optimize pricing strategies, and improve customer retention.
        </p>
    </section>

    <section>
        <h2>🎯 Executive Problem Statement</h2>

        <p>
            Hotels and travel agencies struggle with:
        </p>

        <ul>
            <li>High booking cancellation rates</li>
            <li>Revenue leakage</li>
            <li>Unoptimized room pricing</li>
            <li>Poor demand forecasting</li>
        </ul>

        <p>
            Traditional systems lack predictive intelligence to anticipate customer cancellations
            and dynamically adjust room rates based on market demand and seasonality.
        </p>

        <p>
            This project provides analytical insights to support:
        </p>

        <ul>
            <li>Dynamic pricing strategies</li>
            <li>Customer retention campaigns</li>
            <li>Revenue optimization</li>
            <li>Demand forecasting</li>
        </ul>
    </section>

    <section>
        <h2>🎯 Business Objectives</h2>

        <ul>
            <li>Reduce customer cancellation rates</li>
            <li>Improve customer retention</li>
            <li>Optimize Revenue Per Available Room (RevPAR)</li>
            <li>Understand seasonal demand trends</li>
            <li>Enable data-driven pricing decisions</li>
        </ul>
    </section>

    <section>
        <h2>📊 Key Performance Indicators (KPIs)</h2>

        <table>
            <tr>
                <th>KPI</th>
                <th>Description</th>
            </tr>

            <tr>
                <td>Total Bookings</td>
                <td>Total hotel reservations</td>
            </tr>

            <tr>
                <td>Cancellation Rate</td>
                <td>Percentage of cancelled bookings</td>
            </tr>

            <tr>
                <td>Average Lead Time</td>
                <td>Average days before arrival</td>
            </tr>

            <tr>
                <td>Average ADR</td>
                <td>Average Daily Room Rate</td>
            </tr>

            <tr>
                <td>Revenue Trends</td>
                <td>Revenue performance over time</td>
            </tr>

            <tr>
                <td>Retention Score</td>
                <td>Repeat guest contribution</td>
            </tr>
        </table>
    </section>

    <section>
        <h2>🗂️ Dataset Information</h2>

        <table>
            <tr>
                <th>File</th>
                <th>Description</th>
            </tr>

            <tr>
                <td>Uncleaned hotel_bookings.csv</td>
                <td>Raw hotel booking dataset</td>
            </tr>

            <tr>
                <td>cleaned_hotel_bookings.csv</td>
                <td>Processed and cleaned dataset</td>
            </tr>

            <tr>
                <td>EDA_hotel_bookings.ipynb</td>
                <td>Exploratory Data Analysis notebook</td>
            </tr>

            <tr>
                <td>ML_customer_retention and dynamic pricing.ipynb</td>
                <td>Machine Learning notebook</td>
            </tr>
        </table>
    </section>

    <section>
        <h2>⚙️ Technologies Used</h2>

        <ul>
            <li>Python</li>
            <li>Pandas</li>
            <li>NumPy</li>
            <li>Matplotlib</li>
            <li>Seaborn</li>
            <li>Scikit-learn</li>
            <li>Power BI</li>
            <li>Jupyter Notebook</li>
        </ul>
    </section>

    <section>
        <h2>🧹 Data Cleaning Process</h2>

        <p>
            The dataset contained missing values, duplicate records,
            incorrect data types, and categorical inconsistencies.
        </p>

        <h3>Cleaning Steps</h3>

        <ul>
            <li>Handled missing values</li>
            <li>Removed duplicates</li>
            <li>Converted date columns</li>
            <li>Encoded categorical variables</li>
            <li>Performed feature engineering</li>
            <li>Handled outliers</li>
        </ul>

        <h3>Example Transformations</h3>

<pre>
<code>
df['arrival_date_month'] = pd.to_datetime(
    df['arrival_date_month'],
    format='%B'
).dt.month
</code>
</pre>

<pre>
<code>
df = pd.get_dummies(
    df,
    columns=['hotel', 'deposit_type', 'customer_type'],
    drop_first=True
)
</code>
</pre>

    </section>

    <section>
        <h2>📈 Exploratory Data Analysis (EDA)</h2>

        <h3>Key Insights</h3>

        <ul>
            <li>Longer lead times resulted in higher cancellation rates</li>
            <li>Transient customers dominated hotel bookings</li>
            <li>Corporate customers showed stronger retention</li>
            <li>ADR increased during peak seasons</li>
            <li>Weekend pricing improved profitability</li>
        </ul>
    </section>

    <section>
        <h2>🤖 Machine Learning Analysis</h2>

        <p>
            Machine learning models were developed to predict booking cancellations
            and support pricing optimization strategies.
        </p>

        <h3>Models Used</h3>

        <ul>
            <li>Logistic Regression</li>
            <li>Decision Tree Classifier</li>
            <li>Random Forest Classifier</li>
        </ul>

        <h3>Features Used</h3>

        <ul>
            <li>Lead Time</li>
            <li>ADR</li>
            <li>Deposit Type</li>
            <li>Customer Type</li>
            <li>Market Segment</li>
        </ul>
    </section>

    <section>
        <h2>📊 Power BI Dashboards</h2>

        <h3>1️⃣ Customer Retention Dashboard</h3>

        <ul>
            <li>Cancellation trends</li>
            <li>Customer segmentation</li>
            <li>Retention analysis</li>
            <li>Lead time vs cancellation</li>
        </ul>

        <div class="dashboard">
            <img src="customer_retention_dashboard.png" alt="Customer Retention Dashboard">
        </div>

        <h3>2️⃣ Dynamic Pricing Dashboard</h3>

        <ul>
            <li>Revenue trends</li>
            <li>ADR trends</li>
            <li>Seasonality analysis</li>
            <li>Market segment pricing</li>
        </ul>

        <div class="dashboard">
            <img src="dynamic_pricing_dashboard.png" alt="Dynamic Pricing Dashboard">
        </div>

    </section>

    <section>
        <h2>📌 Business Recommendations</h2>

        <h3>Customer Retention</h3>

        <ul>
            <li>Implement loyalty programs</li>
            <li>Use personalized customer campaigns</li>
            <li>Reduce cancellation risk through deposit strategies</li>
        </ul>

        <h3>Dynamic Pricing</h3>

        <ul>
            <li>Apply seasonal pricing adjustments</li>
            <li>Increase ADR during high-demand periods</li>
            <li>Use predictive demand forecasting</li>
        </ul>
    </section>

    <section>
        <h2>🚀 Future Enhancements</h2>

        <ul>
            <li>Real-time pricing engine</li>
            <li>Advanced forecasting models</li>
            <li>Deep learning churn prediction</li>
            <li>Live booking system integration</li>
        </ul>
    </section>

    <section>
        <h2>📁 Project Structure</h2>

<pre>
<code>
project/
│
├── data/
│   ├── Uncleaned hotel_bookings.csv
│   └── cleaned_hotel_bookings.csv
│
├── notebooks/
│   ├── EDA_hotel_bookings.ipynb
│   ├── Customer Retention and Dynamic Pricing Analysis.ipynb
│   └── ML_customer_retention and dynamic pricing.ipynb
│
├── dashboards/
│   ├── Customer Retention Dashboard.pbix
│   └── Dynamic Pricing Dashboard.pbix
│
└── README.html
</code>
</pre>

    </section>

    <section>
        <h2>👨‍💻 Author</h2>

        <p><strong>Shahil Farshad</strong></p>
        <p>Data Analytics & Business Intelligence Enthusiast</p>
    </section>

</div>

<footer>
    © 2026 Customer Retention & Dynamic Pricing Analysis Project
</footer>

</body>
</html>
