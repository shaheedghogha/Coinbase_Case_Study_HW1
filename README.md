# Coinbase_Case_Study_HW1

## **Overview and Origin**

![](https://images.ctfassets.net/q5ulk4bp65r7/41yyFbvLQOPJ8wGrZVQqMp/e5b0c2a3405e258d3bb44b1bfd4ad768/founders.png)

In 2010, Coinbase Co-founder and CEO read the Bitcoin whitepaper written by pseudonymous Bitcoin creator Satoshi Nakamoto. As a student of economics and computer science, Armstrong realized the value of an open, decentralized protocol utilized to move value around the globe. From there, Armstrong, along with fellow co-founder Fred Ehrsam, set out on a mission to make blockchain technology more accessible by creating a hosted Bitcoin wallet. His vision was to build a platform similar to that of GitHub and Gmail where users could leverage cloud compute and security to custody digital assets
Coinbase kicked off its initial seed round funding in Q3 of 2012, where the company raised $600,000 across six investors. Since then, Coinbase has raised nearly $550M over 16 funding rounds, with the majority ($300M) coming from a Series E funding round led by Tiger Global Management in October 2018.

## **Business Activities**
Coinbase streamlines the procurement and custody of digital assets for traders, investors, and merchants. The Coinbase platform currently supports over 73M customers, 10,000 institutions, and 185,000 ecosystem partners in over 100 countries. More specifically, Coinbase looks to efficiently match buyers and sellers trading any given size of a particular digital asset. 

While Coinbase primarily acts as a fiat on an off-ramp for investors, the organization also looks to help investors use their crypto in novel ways. Coinbase released the Coinbase wallet in 2021, enabling users to self-custody crypto assets and interact with decentralized finance (DeFi) protocols. In addition, Coinbase differentiates itself from competitors by providing a suite of products that users can access through a single platform. Other products from Coinbase include:
* **Coinbase Prime**: An institutional-grade trading platform 
* **Coinbase Custody**: A digital asset custody service for institutional investors
* **Coinbase Card**: A Visa debit card that enables customers to spend cryptocurrency
* **Coinbase Commerce**: A platform that allows businesses to receive crypto payments
* **Coinbase Earn**: An e-learning platform that allows users to earn cryptocurrency by learning through videos and quizzes

In Q4 of 2021, Coinbase announced plans to launch an NFT marketplace. Global NFT sales reached $25B in 2021, with nearly $14B captured by Ethereum decentralized application, OpenSea. Coinbase intends to launch its NFT marketplace sometime in the first half of 2022.

Coinbase's IT infrastructure currently leverages AWS services for Amazon Identity Access Management (IAM), Amazon Elastic MapReduce (EMR), Amazon Relational Database Service (RDS), Amazon Elastic Compute Cloud (EC2), Amazon Simple Storage Services (S3), AWS Lambda, and Amazon Virtual Private Cloud (VPC), Amazon WorkSpaces, Amazon Kinesis, and AWS CloudTrail:
* _AWS Lambda_ and _Amazon S3_ are leveraged for cloud compute (Lambda), storage (S3), and _Amazon EC2_ is also used to provide compute for the Coinbase Exchange
* _Amazon IAM_ allows secure controls access to Amazon Web Services through automated alerts when parameters such as network access controls are changed
* _Amazon RDS_ enables the setup, operation, and scaling of relational databases in the cloud
* _Amazon EMR_ is used by Coinbase for big-data insights, _Amazon Kinesis_ for big-data processing, and _AWS CloudTrail_ to integrate the insight pipeline
* _Amazon VPC_ is used in tandem with Amazon WorkSpaces to provide workers with cloud-based desktops

![](https://images.clickittech.com/2020/wp-content/uploads/2018/01/20201632/aws-services.jpg)

Coinbase also leverages Google Analytics, Mixpanel, Authy, HackerOne, and Blockscore. From a DevOps perspective, Coinbase uses New Relic, CircleCI, Bugsnag, and GeoEngineer. Coinbase business tools include G-Suite and Olark. Coinbase internal applications for use include NGINX, CloudFlare, Ruby, Rails, D3.js, and IronMX.

## **Landscape:**

Coinbase falls into the Blockchain and Cryptocurrencies domain of the financial industry. Mainstream adoption of blockchain and cryptocurrencies has grown exponentially since the inception of Bitcoin. In particular, decentralized finance (DeFi) has captured significant attention and investor capital from both institutional and retail investors. DeFi aims to disintermediate financial services to increase inclusivity and adoption across the banked and unbanked, similar to Coinbase's mission of bringing cryptocurrency services to the masses. 

The other major centralized exchanges in the Blockchain and Cryptocurrencies domain include Binance, FTX, and Kraken. The top decentralized exchanges include Uniswap, PancakeSwap, Curve Finance, and Sushiswap. 

## **Results**
The most notable business impact of Coinbase is the streamlining of cryptocurrency trading for retail investors. The Coinbase app was instrumental in growing the userbase of cryptocurrency retail investors. In recent years, Coinbase Prime has furthered the growth of cryptocurrencies by providing white-glove services to large institutional investors. Furthermore, the company's willingness to embrace DeFi will likely have an even outsize impact on the global adoption of decentralized applications.

The core metrics centralized cryptocurrency exchanges use for success are YOY revenue, profit, and user growth. Coinbase has performed exceptionally across all three of these key metrics, as evidenced by the following data from 2016 to the first half of 2021:
* **2016** - _Revenue:_  16M;     _Profit:_ N/A;            _Users:_ 5M      
* **2017** - _Revenue:_ 927M;     _Profit:_ 380;            _Users:_ 13M
* **2018** - _Revenue:_ 520M;     _Profit:_ 55M (estimate); _Users:_ 22M
* **2019** - _Revenue:_ 483M;     _Profit:_ 30M (estimate); _Users:_ 30M
* **2020** - _Revenue:_ 1.14B;    _Profit:_ 322M;           _Users:_ 35M
* **2021 (H1)** - _Revenue_ 4.03B; _Profit:_ 2.35B;        _Users:_ 56M

Coinbase ranks second to centralized cryptocurrency exchange Binance when comparing revenue, profit, and users. Binance has expanded faster than Coinbase due to ambiguity from a regulatory standpoint. Binance does not have a headquarters, allowing the company to operate outside of regulatory oversight. However, many countries are starting to enforce restrictions on Binance services offered to citizens. Even still, Binance's core metrics measure an order of magnitude ahead of its competitors. In 2021 alone, Binance generated $20B in revenue across 28.6M users.

## **Recommendations**
If I were to advise Coinbase regarding products and services they should offer, I would suggest that the company build out a crypto derivatives platform. One of the reasons why Binance is so much further ahead of Coinbase in terms of user and revenue growth is that Binance has a derivatives platform. I believe a derivatives platform would significantly reduce the gap in core metrics between the two companies. From an IT infrastructure perspective, Coinbase's AWS footprint would need to grow to accommodate a derivative platform, specifically the AWS compute (i.e. Lambda, EC2) and storage (S3) environments would need to scale up. AWS services are ideal in this instance because they would allow the Coinbase IT team to leverage existing AWS skillsets within the organization to build critical infrastructure for the prospective crypto derivatives platform. Furthermore, Amazon Web Services enable the team to scale cloud resources up and down on an as-needed basis.

## **Works Cited** 
1. https://www.cbinsights.com/research/report/coinbase-strategy-teardown/#:~:text=Coinbase%20was%20founded%20in%20July,%2C%20sell%2C%20and%20store%20bitcoin (Coinbase Organizational Overview)
2. https://www.youtube.com/watch?v=O1l2eFW4L0A (Bankless Podcast with Brian Armstrong)
3. https://www.benzinga.com/markets/cryptocurrency/21/04/20660641/coinbase-ceo-brian-armstrong-on-his-companys-beginnings-satoshis-whitepaper-sleeping-in-of (Coinbase Beginnings)
4. https://www.crunchbase.com/organization/coinbase/company_financials (Coinbase Funding)
5. https://www.reuters.com/markets/europe/nft-sales-hit-25-billion-2021-growth-shows-signs-slowing-2022-01-10/#:~:text=NFT%20sales%20volume%20totalled%20%2424.9,%2C%20DappRadar%2C%20said%20on%20Monday (NFT sales in 2021)
6. https://stackshare.io/coinbase/coinbase (Coinbase Tech Stack)
7. https://aws.amazon.com/solutions/case-studies/coinbase/#:~:text=For%20additional%20big%2Ddata%20insight,managed%20petabyte%2Dscale%20data%20warehouse (Coinbase AWS Case Study)
8. https://coinmarketcap.com/rankings/exchanges/ (Top Centralized Exchanges)
9. https://coinmarketcap.com/rankings/exchanges/dex/ (Top Decentralized Exchanges)
10. https://www.businessofapps.com/data/coinbase-statistics/ (Coinbase YOY Revenue, Profit, and User Growth)
11. https://www.businessofapps.com/data/binance-statistics/ (Binance YOY Revenue, Profit, and User Growth)
12. https://boardroom.tv/opensea-nft-sale-surge/#:~:text=Of%20the%20%2420%20billion%20in,in%20sales%20volume%20in%202021 (OpenSea Revenue)
13. https://images.ctfassets.net/q5ulk4bp65r7/41yyFbvLQOPJ8wGrZVQqMp/e5b0c2a3405e258d3bb44b1bfd4ad768/founders.png (Picture of Coinbase Co-Founders)
14. https://images.clickittech.com/2020/wp-content/uploads/2018/01/20201632/aws-services.jpg (AWS Stack)