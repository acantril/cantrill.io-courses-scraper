# cantrill.io Courses Scraper

Welcome to cantrill.io Courses Scraper.

This simple Serverless application scrapes Adrian Cantrill's AWS courses to generate an output `index.html` file and upload it to an S3 bucket hosting a static website.

The content in the generated `index.html` file addresses a freqeuntly asked question regarding the total duration of any of Adrian's courses.

The solution is currently deployed and can be viewed by visting http://cantrill.io-courses-duration.s3-website.ca-central-1.amazonaws.com