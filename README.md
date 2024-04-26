

# ML-Classification-Customer-Churn-Prediction
A telecom company wants to find out the likelihood of a customer leaving the company. This classification model that predicts if a customer will churn or not.

## Summary
Summary
| Code | Name                                     | Published Article             | PowerBi Dashboard |
|------|------------------------------------------|-------------------------------|-------------------|
| LP2  | ML-Classification-Customer-Churn-Prediction | [Medium AT](https://medium.com/p/a84238c34acb/edit) | [POWER BI](https://app.powerbi.com/groups/me/reports/70a3e233-1733-4eb0-bb76-b55149629010/ReportSection?experience=power-bi)          |


## Project Description
In this project, we aim to find the likelihood of a customer leaving the organization, the key indicators of churn as well as the retention strategies that can be implemented to avert this problem. The data for this project is in a csv format. The following describes the columns present in the data.


- Gender-- Whether the customer is a male or a female

- SeniorCitizen -- Whether a customer is a senior citizen or not

- Partner -- Whether the customer has a partner or not (Yes, No)

- Dependents -- Whether the customer has dependents or not (Yes, No)

- Tenure -- Number of months the customer has stayed with the company

- Phone Service -- Whether the customer has a phone service or not (Yes, No)

- MultipleLines -- Whether the customer has multiple lines or not

- InternetService -- Customer's internet service provider (DSL, Fiber Optic, No)

- OnlineSecurity -- Whether the customer has online security or not (Yes, No, No Internet)

- OnlineBackup -- Whether the customer has online backup or not (Yes, No, No Internet)

- DeviceProtection -- Whether the customer has device protection or not (Yes, No, No internet service)

- TechSupport -- Whether the customer has tech support or not (Yes, No, No internet)

- StreamingTV -- Whether the customer has streaming TV or not (Yes, No, No internet service)

- StreamingMovies -- Whether the customer has streaming movies or not (Yes, No, No Internet service)

- Contract -- The contract term of the customer (Month-to-Month, One year, Two year)

- PaperlessBilling -- Whether the customer has paperless billing or not (Yes, No)

- Payment Method -- The customer's payment method (Electronic check, mailed check, Bank transfer(automatic), Credit card(automatic))


- MonthlyCharges -- The amount charged to the customer monthly

- TotalCharges -- The total amount charged to the customer

- Churn -- Whether the customer churned or not (Yes or No)

## 🚀  Some Tools Used For The Project

vscode, pandas, numpy, python, jupyter

## Process
- Pull data from remote database with pyodbc; save as csv files

- Develop questions and a hypothesis to base analysis of the project on

- Understand the data and make decisions on how to process the data

- Data preprocessing, cleaning and merging- The data was very messy and 90% of the project involved cleaning and making the data ready for analysis and visualizations

- Visualise the data with seaborn and pyplot

- Created a PowerBI dashboard with the visualizations

- Wrote a medium article and briefly described the process, findings and recommendations

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>


To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

- Python


### Setup

Clone this repository to your desired folder:


```sh
  cd my-folder
  git clone https://github.com/OngomaElias/Customer_Churn-Prediction
```

Change into the cloned repository

```sh
  cd Customer_Churn-Prediction
  
```

Create a virtual environment

```sh

python -m venv env

```

Activate the virtual environment


```sh
    env/Scripts/activate
```


### Install

Here, you need to recursively install the packages in the `requirements.txt` file using the command below 

```sh
   pip install -r requirements.txt
```


### Usage

To run the project, execute the following command:


```sh
    streamlit run 1_🏠_Home.py

```



<!-- AUTHOR -->

## 👥 Authors <a name="authors"></a>

🕵🏽‍♀️ **Elias Ongoma**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>



  
  
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you like this project kindly show some love, give it a 🌟 **STAR** 🌟

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

I would like to thank all the free available resource made available online

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
