# static-website-host
**Project Overview**
The cloud is perfect for hosting static websites that only include HTML, CSS, and JavaScript files that require no server-side processing. In this project, deployed a static website to AWS. Firstly, created an S3 bucket, configured the bucket for website hosting, and secured it using IAM policies. Next, uploaded the website files to your bucket and speed up content delivery using AWS’s content distribution network service, CloudFront. Lastly, accessed the website in a browser using the unique S3 endpoint.

# STEPS OF THE PROJECT
1.Create a S3 bucket where need to uncheck “Block all public access”.

2.Upload the files and folders from your local computer to the S3 bucket.

3.Change the Bucket Policy according to your Bucket Policy file.

4.Make the bucket to host a website using bucket properties tab.

5.Use CloudFront dashboard create distribution and S3 bucket name use under “Origin Domain Name”

6.Open a web browser like Google Chrome and paste the copied endpoint URL and append “/index.html” on the end.


![sw](https://github.com/Sid-2503/static-website-host/assets/89977643/55af5a71-e4f9-4d2d-8a8b-1b1e1f1c224d)
![sw2](https://github.com/Sid-2503/static-website-host/assets/89977643/7a88f877-11ae-414c-9ad5-2a297ebcb782)
![sw3](https://github.com/Sid-2503/static-website-host/assets/89977643/be58f926-066c-473c-9f89-90c76264ab6a)

