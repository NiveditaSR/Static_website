The static website I created is for the demonstration for deploying the website in S3 bucket and accessing it through the URL.

A static website does not require server-side processing; it only delivers the website's content. 
It consists of fixed pages that are pre-built and stored, meaning that every visitor sees the same information and layout every time they access the site.



Here is how I configured the settings,

1) Create a bucket, say bakery_order_site. NOTE: Uncheck the bucket policy and create a simple bucket policy using bucket policy generator.

2) Upload the code and images related to the website.

3) Go to the properties section of the bucket, enable the static website hosting

4) There are two hosting types,

     a) Host a static website, serving the static content directly from the S3 bucket.

     b) Redirect requests for an object, an option to redirect requests from one domain (or bucket) to another.  

Choose the hosting type (a) for now. And mention the default page and an error page.

You will be given a URL, once the setting is configured. Paste the URL into the browser to see the site. 

