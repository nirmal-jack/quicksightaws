# Visualize Data with AWS QuickSight

-  Download the top 50 selling brands in the last month data using BrightData. Bright data gives us the real-time data to keep the projects more interesting.
-  Create a s3 bucket with the name "nirmal-amazon-project"
  ![s3 bucket](https://github.com/nirmal-jack/quicksightaws/assets/170439621/0b6363ed-6ed7-4d7d-bd2a-2befed963de1)
 - Change the correct name of the s3 bucket in the json file.
- Upload the downloaded data file and the json file given by BrightData into the S3 Bucket.

![uploaded files](https://github.com/nirmal-jack/quicksightaws/assets/170439621/159ce0ba-04de-4cd7-b98d-f56bbc370ac3))(![updated files](https://github.com/nirmal-jack/quicksightaws/assets/170439621/99622a20-2431-4e5d-b189-05ba8cec1dcb)

- Go the aws console, and open quicksight.
- SignUp for quicksight, if you are new and can cancel the subcription 30 days before.
- Choose Amazon S3 and choose the bucket created and give finish.
- The quicksight account gets created instantly.
- Click on dataset, new dataset and choose S3. 
- Go over to the console and choose the bucket that we have created. "nirmal-aws-project" and choose the manifest file.
- Select the "COPY S3 URL" Option.
- give the URL and choose connect.
- Select visualize.
- Click create and the data gets set up.
- Drag and drop the colum brand inside the graph.
- Now to arrange the brands in ascending order, we can see which brands are the most popular, click on brands on the graph>> sort options>> ascending.





