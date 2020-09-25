# NLP-sample
This program allows you to scrap the Timestamp and the url via archive.org API of the nearest date to the 1st of each month since the start date. It outputs a csv file that contains the Timestamp and the url of a specific website.

For the variable 'time', enter the start date that you want for the webpage snapshots scrapper. For the variable 'website', enter the url of the website.

About the result:
There is a potential problem about the output result. The archive.org API will automatically fetch the nearest available snapshots of the website on the designated date. But sometimes, although url is ‘available’ on the archibe.org,  the url does not really direct to a snapshot. Instead, it returns an error note like this:

[Error.png](https://postimg.cc/7G0SBpzK)

To further solve problems like this, a rather detailed target content should be specified so that we filter out snapshots that do not contain target content.

For any other questions, please contant yli34818@usc.edu
