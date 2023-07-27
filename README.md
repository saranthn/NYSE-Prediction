<a name="readme-top"></a>
# New York Stock Exchange Dtock Price Forecasting

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#models">Models</a></li>
    <li><a href="#conclusion">Conclusion</a></li>
    <li><a href="#contributors">Contributors</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Stock and financial data have historically been an important and popular topic to analyze and draw inferences from. In this project, we will attempt to use machine learning on stock prices and financial data to predict one-day ahead stock prices. A large issue that comes from trying to use machine learning on financial data is that they are very noisy, and it is challenging to distinguish between signal and noise. We plan to predict stock prices from 5 companies (Pfizer (PFE), Exxon Mobil (XOM), Wells Fargo (WFC), Microsoft (MSFT), and McDonald’s (MCD)) using their historical closing price data from the New York Stock Exchange from 2010 - 2017.

Report: '.\'

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Built With

* ![Python]
* sklearn
* matplotlib
* tensorflow
* matplotlib
* seaborn
* numpy
* statsmodels

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Models

* LSTM
* Rolling Regression
* ARIMA

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Conclusion

Of our three models, it seems that rolling regression performs the best in terms of RMSE and MAE while LSTM and ARIMA performed similarly to each other but worse than the rolling regression. The LSTM model could further be improved by possibly feeding in more data and trying different architectures. We could also add in additional covariates using fundamental information from the other data sets. Overall, our models performed fairly well in capturing the data in the limited time periods that we had.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributors

* Saravanan Thanu
* Kennis Kong
* Harshini Ramanujam

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[Python]: https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white
[AWS]: https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white
[Youtube]: https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white
