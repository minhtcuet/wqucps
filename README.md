Application of machine learning in algorithmic investment strategies: The case of US and China stock markets

WordQuant Capston project

Members:

Thao Dang, Minh Tran, Vuong Chu

ABSTRACT
As machine learning techniques have become increasingly popular for developing effective investment strate-
gies, our project aims to explore the application of machine learning algorithms (classification and regression) to
construct stock selection strategies. We would use daily data from January 1, 2014, to December 31, 2018, on the
S&P 500 index and CSI 300 index and generate features and labels based on stock performance. By back-testing
strategies using historical data, our empirical results highlight some key findings: Firstly, XGBoost outperforms
Deep Neural Network and Random Forest in designing the strategy. This result is robust no matter how many stocks
are picked to build up the trading signals. Secondly, normal trading is better than day trading when applying our
strategy. Thirdly, while vertical ensemble improves the performance of our strategy, horizontal ensemble does not.
Finally, by combining both classification and regression, our model significantly improves the efficiency of the in-
vestment strategy with a positive annualized return and a relatively high Sharpe ratio. The results are robust across
two markets, which shows that we can apply this investment strategy into practice.


- Create Virtual Environment

>> conda create -n wquc python=3.10


- Activate Created Virtual Environment

>> conda activate wquc


- Install libraries

>> pip3 install -r requirements.txt
> 
> 
> 
