# gyazoCrawler

**gyazoCrawler is a python scrip to index and download Gyazo screenshots.**

Usage
--
Edit the ```main.py``` file variables with your cookies and files/folders. Run it with py2 and you will have 2 main options:
1. Index database of gyazos - will fetch gyazo.com and create your database of links;
2. Calculate the size and download the all the images from the DB - will calculate the size from the database file, and then ask if you want them to be downloaded, if so they will go on the specified folder. (note that the size value is calculated by the ```"file_size"``` key, and some images may not have this)


Dependencies 
--
- [Requests] - Python HTTP Requests for Humans


Disclaimer
--
I'm not affiliated with Gyazo in any way.

For the Gyazo team/company:
 - I could not find anything that explicitly said, that this practice of recovering and downloading old *gyazos* was against your policy.
 - I completely understand that you may not like this, if you want to stop it you should  remove 
```"url"```,```"permalink_url"``` and ```"permalink_path"``` 
from the JSON response
 - If you wish the removal of this repo just tweet me [@tofran_] and I’ll do it as soon as possible.


License
--
MIT


[@tofran_]:https://twitter.com/tofran_
[requests]:https://github.com/kennethreitz/requests