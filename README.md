# Instagram-crawling
This program is :
* how to access the list of level 2 followers from the target account data using Breadth First Search (BFS) implementation.
* find most likes and most tag in post
* saving .json data above into mongodb 
* circumvent instagram rate limit


## Below is what you can do with this program:
Get Instagram username/posts/hashtag/likes/comments data using Breadth First Search (BFS) implementation without using Instagram API but use used methods and structures as a Python module. 

### Documentation
Please read: 
* [Instaloader](https://instaloader.github.io/as-module.html) for details about instagram crawling data
* [Instaloader](https://pypi.org/project/instaloader/)
* [pandas] (https://pypi.org/project/pandas/) for details
* [mongo guide install](https://www.geeksforgeeks.org/guide-install-mongodb-python-windows/) or read [mongo python driver](https://www.w3resource.com/mongodb/mongodb-python-driver.php)
* [pymongo](https://pypi.org/project/pymongo/) for details about tools for interacting with MongoDB database from Python 
* [time.sleep()] (https://www.geeksforgeeks.org/sleep-in-python/) to circumvent instagram rate limit

### Prerequisites
* install Instaloader ```pip install instaloader``` 
* install pandas ```pip install pandas```
* install pymongo in ```python pip install pymongo```
* install mongodb [mongodb](https://www.mongodb.com/dr/fastdl.mongodb.org/win32/mongodb-win32-x86_64-2008plus-ssl-3.4.10-signed.msi/download)

#### Instagram Crawler
save both of them into same directory ```insta.py``` & ```Main.py```
* run this  ```Main.py``` - to get username/posts/hashtag/likes/comments data in your own text editor. output of this program is a .csv file.

#### Find Most Likes and Most Tag in Post


#### MongoDB
run ```tes_mongo.py``` to access dataset in mongodb


## Output
* Output csv file from ```Main.py``` is ```dataframe.csv``` 


* ![Output from ```InstaData.py``` ](InstaDataOutput.png) 



