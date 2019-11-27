# AWS Meetup 22 Nov 2019 Chennai

This repo includes the presentation and demo videos for the Meetup session on Glue.

This section was conducted by Madan Kapoor from Coda Global.

## Demo Videos

I have included short videos for creation of a crawler to crawl a csv file and a Glue job to do a simple CSV to parquet.



## Reinvent Videos for reference

https://www.youtube.com/watch?v=eQBHIINW8VY
https://www.youtube.com/watch?v=S_xeHvP7uMo
https://www.youtube.com/watch?v=JsNR8uBVSiA


## Simple Tips and Tricks.

1. If you are using spark dataframe please use glue connection with boto lib to get your credentials to datasource.

2. Version you code in S3 to revert back if you find issues through pipelines.

3. Combine smaller jobs to into single job to avoid cold start and save some money.

4. Use Glue mertics to figure out the balance between paritions and executers.

5. Perfer using Dynamic Dataframe for AWS sources like redshift and S3, aws provides memory optimisation for it.


## Use Full Links

https://docs.aws.amazon.com/glue/latest/dg/aws-glue-programming-etl-libraries.html

https://docs.aws.amazon.com/glue/latest/dg/dev-endpoint-tutorial-local-notebook.html


## Eg Use Cases

https://docs.aws.amazon.com/glue/latest/dg/aws-glue-programming-python-samples-legislators.html

https://aws.amazon.com/blogs/big-data/streamline-aws-cloudtrail-log-visualization-using-aws-glue-and-amazon-quicksight/

https://docs.aws.amazon.com/glue/latest/dg/machine-learning-transform-tutorial.html


## Contact:

Please feel free to reach out to me by any means.

Email: madankapoor10@gmail.com

Phone Number: 91 8778002946

linkedin: https://www.linkedin.com/in/madankapoor10/
