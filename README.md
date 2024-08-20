# LMS

## Project Description
With the rise of e-learning, there is a need for a comprehensive online platform that can deliver educational content to a wide range of learners. This platform should support various content formats, track learner progress, and provide interactive tools to enhance the learning experience. It must be scalable to accommodate a growing number of users and a broad catalog of courses.

### Working 
As our project needed the multi media content we uploaded the content of the courses like video's and materials in the S3 bucket created. As we need to play the content video's with low latency. So, we added video's from S3 bucket to cloud front. Now we  generated the links for the video's from the cloud front and links for the materials from the S3 bucket. The links that we collected from s3 and cloudfront have been attached to the html files so that it can be easily redirected. In our project we need to conduct the skill assessment for our courses so we need backend process to be done. For the backend process we created  lambda functions to generate the marks. Once we done with our lambda part we created API gateway and got the API gateway link so that we can connect our frontend and backend part. Once we completed our frontend part(HTML, CSS, JavaScript), we uploaded all the code files in EC2 instance and launched a website. And last but not the least we created cloud watch to monitor the system and provide the analytics.

### Architecture
![image](https://github.com/user-attachments/assets/ba240614-cb0c-4c0b-b2ee-eaa211020fed)


In my github you can also check the codes files of the project Repository named AWS-Online-Learning-Management-System but you cann't see the page live because the we used Amazon EC2 instance to host the website now the instance is currently turned off.

For futher check this out https://github.com/DogiparthiAasrith/AWS_Online-Learning-Management-System
