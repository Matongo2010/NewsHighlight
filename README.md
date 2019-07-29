## Description

'News' is an application that displays a list of news sources from around the globe and a user is able to get informed by clicking on the provided news source. Clicking on the news article will redirect you to the news article web page.
A user  can be able to see various news sources and pick the ones they prefer. They can also see the image description and the time the news article was created.

## BDD
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Display news sources | List of various news sources is displayed per category |
| Display articles from a news source | Redirected to a page with a list of articles from the source |
| Display the preview of an article | Each article displays an image, title, description and publication date |
| Read an entire article  | Redirected to the news source's site to read the entire article |

## Getting started

* Clone the repository to your local computer.
* Navigate to the cloned project folder.
* Create a virtual environment and access the folder via virtual machine.
* Create start.sh file and in it write the following lines:
```
 export NEWS_API_KEY='<Your-Api-Key>'
 python3.6 manage.py server
```
* Run ```chmod +x start.sh``` follwoed by ``` ./start.sh ``` while in the project folder to start the project.
* Once started, the project can be accessed on your localhost using the address: ``` localhost:5000 ```.

## Technologies used

Python 3.6
Flask

## Licence

Copyright (c) 2019 Adriano Meroka