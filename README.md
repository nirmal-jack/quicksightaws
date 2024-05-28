# Visualize Data with AWS QuickSight

-  Download the top 50 selling brands in the last month data using BrightData. Bright data gives us the real-time data to keep the projects more interesting.
-  Create a s3 bucket with the name "nirmal-amazon-project"
  ![](./![image](https://github.com/nirmal-jack/quicksightaws/assets/170439621/54e3674e-c5a4-4d7b-b1a2-75f95de02e35))
- Change the correct name of the s3 bucket in the json file.
- Upload the download data file and the json file given by BrightData into the S3 Bucket.
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





