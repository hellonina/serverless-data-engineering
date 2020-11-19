

<img width="918" alt="스크린샷 2020-11-18 오후 12 21 06" src="https://user-images.githubusercontent.com/71023894/99564512-9070a000-2998-11eb-8fab-a506fe491592.png">

## Project Overview
This data engineering pipleline was built for IDS 706 final project. The goal of this project is to build serverless data pipeline with Amazon Web Services, and ultimately perform a sentiment analysis with wikipedia corpus to find out gender inequality in English language. A number of AWS services were used in this pipeline: SQS, Lambda, S3, Comprehend and CloudWatch. 


## Walk-through
* [Python Code](https://github.com/hellonina/serverless-data-engineering/blob/main/serverless-data-engineering.ipynb)


## Conclusion
The sentiment of 24 names were analyzed with AWS Comprehend. As a result, all 24 names, regardless of its traditional gender associations, were found to have a neutral sentiment with almost 0.99 confidence. We recognized that if the corpus captured more opinions instead of definitions and origins the results might reflect cultural and social sentiment associated with each names. 


## Reference
Professor Gift's github: https://github.com/noahgift/awslambda
