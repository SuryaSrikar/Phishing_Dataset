# Phishing_Dataset

The dataset provided has the phishing attacks occured in the past few days. Here I have used logistic regression and KNN to solve the problem. Both the methods act as classifier.
I also did some feature engineering to imporve the accuracy and F1 Score.

# Introduction

Phishing is the fraudulent attempt to obtain sensitive information such as usernames, passwords and credit card details, often for 
malicious reasons, by disguising as a trustworthy entity in an electronic communication. The word is a neologism created as a homophone of fishing due to the similarity of using a bait in an attempt to catch a victim. The annual worldwide impact of phishing could be as high as US$5 billion.

 Phishing is typically carried out by email spoofing or instant messaging, and it often directs users to enter personal information at a fake website, the look and feel of which are identical to the legitimate site, the only difference being the URL of the website in concern. Communications purporting to be from social web sites, auction sites, banks, online payment processors or IT administrators are often used to lure victims. Phishing emails may contain links to websites that distribute malware.

Phishing is an example of social engineering techniques used to deceive users, and it exploits weaknesses in current web security. Attempts to deal with the growing number of reported phishing incidents include legislation, user training, public awareness, and technical security measures.


# Explore Some Data

Let's take a look at the provided features on our set of URLs.

Create Age (in Months): The age of the domain. If the value is -1, that information is not available or the domain has been deleted.
Expiry Age (in Months): The amount of months until the domain expires. If the value is negative, that information is not available or the domain has been deleted.
Update Age (in Days): The last time the domain was updated. If the value is -1, that information is not available or the domain was deleted.
URL: The URL of the website. Three periods have been added to the end of each URL to prevent the URL from being clicked for security purposes.
Label: A label to determine whether a website is a phishing link or not. 0 denotes a website that is not a phishing link, 1 denotes a website is a phishing link.

