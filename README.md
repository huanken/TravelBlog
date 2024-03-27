# Deploy Static Website on AWS

In this project, I will deploy a static website to AWS using S3, CloudFront, and IAM.

## Website URL: d2d31cis1j6gs6.cloudfront.net
[Travel Blog](d2d31cis1j6gs6.cloudfront.net)

## The files included are: 

- index.html - The Index document for the website.
- /img - The background image file for the website.
- /vendor - Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function.
- /css - CSS files for the website.

## Steps:
### 1. Create S3 bucket with public access
![Create-S3-bucket](./steps-images/Create-S3-bucket.png)
### 2. Upload folders and index.html to bucket
![Upload-file-to-S3](./steps-images/Upload-file-to-S3.png)
### 3. Add permission to S3 bucket
![Add-permission-to-bucket](./steps-images/Add-permission-to-bucket.png)
### 4. Config static website hosting
![Enable-static-website-hosting](./steps-images/Enable-static-website-hosting.png)
### 5. Distribute website via CloudFront
![Distribute-website-via-CloudFront](./steps-images/Distribute-website-via-CloudFront.png)
### 6. Access website in chorme
- With CloudFront domain d2d31cis1j6gs6.cloudfront.net
![Access-website-in-chorme](./steps-images/Access-website-by-CloudFront.png)
- With bucket endpoint http://my-788083028370-bucket.s3-website-us-east-1.amazonaws.com/
![Access-website-in-chorme](./steps-images/Access-website-via-bucket-endpoint.png)
- With object file index.html endpoint
![Access-website-in-chorme](./steps-images/Access-website-via-object-url.png)