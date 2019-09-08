# TXTmedia_sentiment_stock_market_prediction

[<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/banner.png" width="888" alt="Visit QuantNet">](http://quantlet.de/)

## [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/qloqo.png" alt="Visit QuantNet">](http://quantlet.de/) **TXTmedia_sentiment_stock_market_prediction** [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/QN2.png" width="60" alt="Visit QuantNet 2.0">](http://quantlet.de/)

```yaml

Name of QuantLet : TXTmedia_sentiment_stock_market_prediction


Published in : TXT

Description : Prediction of Apple Inc. stock return using BERT-based sentiment index built from NASDAQ News data. 
The sentiment classification algorithms (namely BERT and Support Vector Machine) are trained using Malo et al. (2014)’s « Sentences_66Agree.txt ».  The lexicon-based index is built using Loughran and MacDonald (2011)'s dictionary.
We use LSTM (Hochreiter, S. and J. Schmidhuber(1997)) for prediction and compare the performance depending on the inputs. The controls are the one-month USD LIBOR interest rate, the economic risk premium defined by the difference between the three-month and the one-month interest rates, the USD currency fluctuation using the US dollar index (USDX) as a proxy and the Fama-French 5 factors.

The data for the AAPL stock value and the USD index can be found on Yahoo Finance

The data for the US LIBOR interest rates and the risk premium can be found on http://iborate.com/usd-libor/. 

The data for the Fama-French 5 factors can be found on http://mba.tuck.dartmouth.edu/pages/faculty/ken.french/Data_Library/f-f_5_factors_2x3.html

The NASDAQ News dataset was built by Junjie Hu from the Ladislaus von Bortkiewicz Chair of Statistics of the Humboldt-Universität zu Berlin. This database is available for research purposes at RDC, CRC 649, Humboldt-Universität zu Berlin

The tutorial used for LSTM prediction can be found here: https://machinelearningmastery.com/multivariate-time-series-forecasting-lstms-keras/


Keywords : text mining, sentiment, classification, transfer learning, BERT, support vector machine

See also : TXTfpbsupervisedBERT for BERT sentiment classification performance evaluation

Author : Manuel Tonneau

Submitted : Thu, Sep 13 2019 by Manuel Tonneau
