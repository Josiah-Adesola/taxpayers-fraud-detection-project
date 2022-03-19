# taxpayers-fraud-detection-project

# Problem Statement

There is an increasing number of people camouflaging as taxpayers in India. 
They create a fake Card with their pictures on it.
This has really caused breaches in the security system of the country.
It has affected the revenue entering the country by 68% negatively. 
There hadn't been good allocation of resources presently due to this problem.
The government reached out to us to help them solve this problem.
We discovered that this problem could be solved efficiently with Computer Vision and Machine Learning Models

# Machine Learning Process

Get images from users
Check for the size and format of the image
Change the shape and size of the image according to the original image
Convert the image to grayscale
Find the similarity index of the images
Find the threshold of the image
Finding contour and grab those contour using imutils
Draw a bounding rectangle using these contours
Plot difference, threshold, original and tampered image
Compare all the images and check the similarity score to decide tampering

# Summary

Our SSIM (Structural Similarity Index Mark) is ~31.2%. It made it evident that the user ID is fake.

This project has helped us find similarities and differences between Taxpayers ID Cards to detect fake and fraud.

We found out thresholds and contours based on the threshold for the ijmages converted into grayscale with the help of open-cv package.

This helped in analysis and recognition.

We were also able to visualize the differences between the two images asides teh SSIM.


# Scope

This project can be used in different organizations such as schools, event centers, finance institutions, entry and exit situations, electoral ID PVC and so many others
