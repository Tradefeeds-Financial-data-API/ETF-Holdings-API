# ETF-Holdings-API
<a href="https://tradefeeds.com/etf-holding-api/" rel="nofollow">Tradefeeds ETF Holdings API Database</a> contains real-time and historical data on various types of ETFs: market ETFs, bond ETFs, sector and industry ETFs, commodity ETFs and international ETFs. As Tradefeeds ETF holdings database is currently expanding, more types of exchange-traded funds such as style ETFs, inverse ETFs, actively managed ETFs and exchange-traded notes (ETNs) will be available for usage. 

The data on ETF holdings is available through JSON REST API or retrieved in downloadable excel or csv files. Tradefeeds ETF holdings API database is suitable for use any type customers - from developers who build their applications for a specific audience to in-house teams in all-sized companies. You can find accurate and regulartly updated data on mutual funds. Our team updates the API database daily.

Tradefeeds subscription packages are developed in such a way to serve all customers' needs. For the moment, there is no free trial provided. In case that you are a researcher or a student, we could negotiate a free trial. <a href="https://tradefeeds.com/pricing-subscription-plans/" rel="nofollow">Sign up for an API key</a> and we work out your case.

<h2><a id="user-content-ways-to-access-company-data" class="anchor" href="https://github.com/Tradefeeds-Financial-data-API/Company-information-API#ways-to-access-company-data" aria-hidden="true"></a>Ways to access company data</h2>
<ul>
 	<li><strong>JSON REST API</strong></li>
 	<li><strong>Excel CSV download</strong></li>
 	<li><strong>PDF reports</strong></li>
 	<li><strong>Email link</strong></li>
</ul>

<h2>Documentation</h2>

Our <a href="https://tradefeeds.com/api-documentation/" rel="nofollow">documentation</a> includes input API filtering parameters, output response objects with explanation of their meaning. Clear request and response examples are given on the documentation page. Furthermore, we provide SDKs for Javascript, JQuery, VueJS, Angular, JAVA, PHP, NodeJS, Python, Go, Ruby, C#, R, Strest, Rust, Swift and Scala

<h2>Request and response examples</h2>


<strong>Example: You are searching for data on the ETF holdigns Invesco Inc. has in its portfolio.</strong>
<p><a href="https://tradefeeds.com/api-documentation/">https://tradefeeds.com/api/v1/etfholdings?key=YOUR-KEY&etf_ticker_symbol=QQQ</a></p>


    "status": {
        "message": "Success"
    },
    "results": [
        {
        "basics": {
            "name": "Invesco"
            "etf_ticker_symbol": "QQQ"
            "isin_identifier": "US46090E1038"
            "exchange": "nasdaq"
            "date": "2020:12:31"
            "number_of_holdings": "100"
            },
        "output": {
            "name": "Apple Inc"
            "stock_ticker_symbol": "AAPL"
            "isin_identifier": "US0378331005"
            "exchange": "nasdaq"
            "number_of_holdings": "142,085,775"
            "percent_of_portfolio": "10.99"
            "value_of_holdings": "20,724,631,141.50"
            },
            {
            "name": "Microsoft Corporation"
            "stock_ticker_symbol": "MSFT"
            "isin_identifier": "US0378331005"
            "exchange": "nasdaq"
            "number_of_holdings": "64,127,005"
            "percent_of_portfolio": "9.81"
            "value_of_holdings": "18,401,244,084.75"
             },
            {
            "name": "Amazon.com, Inc."
            "stock_ticker_symbol": "AMZN"
            "isin_identifier": "US0378331005"
            "exchange": "nasdaq"
            "number_of_holdings": "4,293,952"
            "percent_of_portfolio": "8.34"
            "value_of_holdings": "14,136,162,318.72"
             },
            {
            "name": "Facebook, Inc. Common Stock"
            "stock_ticker_symbol": "FB"
            "isin_identifier": "US0378331005"
            "exchange": "nasdaq"
            "number_of_holdings": "20,401,110"
            "percent_of_portfolio": "4.01"
            "value_of_holdings": "7,343,583,555.60"
            }
        }
    
<h2>Customer support</h2>
In case that you encounter a data issue or you want to have more features added to the API, please contact us at support@tradefeeds.com.
 
<h2>Legal</h2>

<p> The use of Tradefeeds proprietary data and API database is subject to the&nbsp;<a href="https://tradefeeds.com/terms-and-conditions-on-data/">Tradefeeds Terms &amp; Conditions.</a></p>
