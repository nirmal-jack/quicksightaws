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
   ![quicksight login](https://github.com/nirmal-jack/quicksightaws/assets/170439621/c7287a5c-7944-4ff0-9662-f7b7e899f806)

- Click on dataset, new dataset and choose S3.
  ![new dataset](https://github.com/nirmal-jack/quicksightaws/assets/170439621/baf7e107-8b49-43ab-be3f-9dc8360de365)

- Go over to the console and choose the bucket that we have created. "nirmal-aws-project" and choose the manifest file.
- Select the "COPY S3 URL" Option.
  ![copy s3 url](https://github.com/nirmal-jack/quicksightaws/assets/170439621/3d756c49-2627-4865-99c1-7052292c4ff4)

- give the URL and choose connect.

![s3 url](https://github.com/nirmal-jack/quicksightaws/assets/170439621/8cf00e78-7274-4933-8953-7881aa567fd6)

  
- Select visualize.


![visualize](https://github.com/nirmal-jack/quicksightaws/assets/170439621/de399031-1df1-4f80-8592-2340fc541643)

- Click create and the data gets set up.

  ![create](https://github.com/nirmal-jack/quicksightaws/assets/170439621/d8db624a-7ee2-4d82-9cc3-4c263a7083b0)

- Drag and drop the colum brand inside the graph.

![brand](https://github.com/nirmal-jack/quicksightaws/assets/170439621/34daa6d5-726b-47f5-9395-120674162376)


- Now to arrange the brands in ascending order, we can see which brands are the most popular, click on brands on the graph>> sort options>> ascending.





