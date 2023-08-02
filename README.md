# static-website-deployment-from-Github-to-S3-using-AWS-CodePipeline

-->>Automate-static-website-deployment-from-Github-to-S3-using-AWS-CodePipeline

Code Pipeline:

		AWS CodePipeline is a fully managed continuous delivery service that helps you automate your release pipelines for fast and reliable application and infrastructure updates.
CodePipeline automates the steps required to release your software changes continuously.

the benefits of using AWS CodePipeline:
		
	*Automated release process:
	*Increased reliability:
	*Scalability:
	*Cost-effective:

Amazon S3(Simple Storage Service) – A highly scalable object storage service. It can be used for a wide range of storage solutions, including websites, mobile applications, backups, and data lakes.

Process : 

	pic 1

	The pipeline is initiated when new items are committed, and the changes are then reflected in the S3 bucket. The Blog will cover the creation of an AWS Account to Automatically deploy the static website from Github to S3 using AWS CodePipeline.



steps to create an automated static website deployment from GitHub to S3 using AWS CodePipeline:

*Create an S3 bucket and configure it for static website hosting.
*Create a GitHub repository and upload your static website files.
*Create a CodePipeline pipeline.
*Configure the source stage of the pipeline to connect to GitHub.
*Configure the deploy stage of the pipeline to deploy your static website to S3.
*Test the pipeline by pushing a change to your GitHub repository.
