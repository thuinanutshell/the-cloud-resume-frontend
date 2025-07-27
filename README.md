# The Cloud Resume Challenge (AWS)
Writing HTML/CSS did not take me much time and I just followed the tutorial to set up AWS S3. The CloudFront is a bit confusing so I used an external resource to follow.

- [x] Your resume needs to be written in HTML. Not a Word doc, not a PDF. Here is an example of what I mean.
- [x] Your resume needs to be styled with CSS. No worries if you’re not a designer – neither am I. It doesn’t have to be fancy. But we need to see something other than raw HTML when we open the webpage.
- [x] Your HTML resume should be deployed online as an Amazon S3 static website. Services like Netlify and GitHub Pages are great and I would normally recommend them for personal static site deployments, but they make things a little too abstract for our purposes here. Use S3.
- [x] The S3 website URL should use HTTPS for security. You will need to use Amazon CloudFront to help with this.
- [ ] Point a custom DNS domain name to the CloudFront distribution, so your resume can be accessed at something like my-c00l-resume-website.com. You can use Amazon Route 53 or any other DNS provider for this. A domain name usually costs about ten bucks to register.

For the last task, I'm using Namecheap to create a domain name called `thu-cloud-resume.me` because Github Student has this offer of free `.me` domain name for students for a year! Then, I follow the setup of CNAMES in CloudFront and Namecheap. The validation time took quite a while so the key is to be patient.

# Resources
[1] https://docs.aws.amazon.com/AmazonS3/latest/userguide/HostingWebsiteOnS3Setup.html

[2] https://aws.amazon.com/awstv/watch/785302d2101/

[3] https://dev.to/aws-builders/setup-cloudfront-amazon-s3-to-deliver-objects-on-the-web-apps-securely-efficiently-2gnk

[4] https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/CNAMEs.html