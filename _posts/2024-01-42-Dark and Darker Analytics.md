---
layout: post
title:  "Dark and Darker Analytics"
date:   2024-01-25
categories: projects
---
# Current State
![Capture](https://github.com/andjnewb/andjnewb.github.io/assets/71988305/26f397ff-3a59-47d4-bd99-5682c50990f4)  
Starting with only the information in the picture above, I have been able to use Roboflow and Tesseract OCR to get data in a database
like the image below. Right now, we can measure weapon volume (since the program began running) and weapon average price.
Pretty neat!

I recently switched the project over to MySQL from MongoDB. I just didn't have the experience with MongoDB to get this project moving,
but MySQL is easy enough for me to handle.

# Issues 
I'm currently having trouble getting a local inference server up and running for Roboflow. It doesn't work on Python 3.12,
so I downgraded everything to Python 3.10. That actually let me install the inference package buttt Docker Desktop just refuses to work on my 
system. I think it is an WSL issue, but no matter what I do I can't get everything working. I don't plan to run the project on this machine full-time 
so maybe I can work around that.

![mysql_example](https://github.com/andjnewb/andjnewb.github.io/assets/71988305/da3c125b-d7f7-4c12-a731-e62f5d004c64)


[my_github]: https://github.com/andjnewb



