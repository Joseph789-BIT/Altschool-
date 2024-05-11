# Exercise on AWS

Create a static and host it on S3 bucket(private bucket) but with public read policy assigned, using cloud front for CDN.

- Create a new distribution

  ![creating a new distribution](Screenshot%20(449).png)

- Here, we set the "Origin domain"

  ![setting the origin domain](Screenshot%20(437).png)

   Origin access
    
    ![setting origin access](Screenshot%20(439).png)

- Click on crete new OAC

  ![creating new OAC](Screenshot%20(440).png)

   Once created, we will be prompted to update our S3 bucket policy once the distribution has been created

   ![](./Screenshot%20(441).png)


- Web application firewall, it's a security control option that protects our website from threats and cyber attacks

- Default root object is the page where we can create policy on from here 

  ![](Screenshot%20(450).png)


  Upon successful creation of distribution, we would promted to add our S3 bucket policy by navigating to the S3 bucket permissions

  ![](Screenshot%20(443).png)

  - Add policy that you copied to the S3 bucket

    ![](Screenshot%20(444).png)

- Go to Cloudfront and into your created distribution and copy the "Distribution domain name to access your website"

 ![](Screenshot%20(446).png)


 Here's what my webpage looks like after pasting my domain name on the browser

 ![](Screenshot%20(448).png)