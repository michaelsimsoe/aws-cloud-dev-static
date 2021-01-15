# AWS Cloud Developer Nanodegree - Static Website on AWS

<img width="1067" alt="Skjermbilde 2021-01-15 kl  22 51 27" style="position: absolute; top: 0; z-index: -1; width: 100vw; left: 0;;" src="https://user-images.githubusercontent.com/16366210/104782586-bf32a900-5784-11eb-85c4-f17f9da008d2.jpg">

<br>
<br>
<br>

<img width="232" alt="Skjermbilde 2021-01-14 kl  20 39 52" src="https://user-images.githubusercontent.com/16366210/104640402-bb315900-56a8-11eb-9b41-e47c28d8eb73.png">

<br>
<br>

> Deploy Static Website on AWS
>
> In this project, you will deploy a static website to AWS using S3, CloudFront, and IAM.

## Lessons learned

- Even though CloudFront has a status of deployd it doesn't mean the changes has taken affect. Hold your horses.
- Resources can have roles.
- If for some reason every other request to the CloudFront domain returns a _403 Forbidden_, set a custom error response with the target (ie redirect to index.html).

## Useful links

- [How do I use CloudFront to serve a static website hosted on Amazon S3?](https://aws.amazon.com/premiumsupport/knowledge-center/cloudfront-serve-static-website/)
- [How do I use my CloudFront distribution to restrict access to an Amazon S3 bucket?](https://aws.amazon.com/premiumsupport/knowledge-center/cloudfront-access-to-amazon-s3/)
- [Give Permissions to an OAI](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/private-content-restricting-access-to-s3.html#private-content-updating-s3-bucket-policies-permissions)
