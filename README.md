# Youtube_comment_Download-Sentiment
a downloader for youtube comments, video is identified by a Keyword, that is supposed to be your video title, in addition to this a sentyment analysis and a wordcloud of the donwloaded comment is done.


Prerequisite :

Python 3

pip(Python Package Index) :

$ sudo apt-get install python3-pip

requests package :

$ sudo pip3 install requests

lxml package :

$ sudo apt-get install libxml2-dev libxslt1-dev python-dev

$ pip3 install lxml

matplotlib package :

$ sudo pip3 install matplotlib

nltk package :

$ sudo pip3 install nltk

wordcloud package :

$ sudo pip3 install wordcloud

Youtube API settings:

Project Setup:

In order to access the YouTube Data API, you need to have a project on Google Console. This is because you need to obtain authorization credentials to make API calls in your application.

Head over to the Google Console and create a new project. One thing to note is that you will need a Google account to access the console.

Click Select a project then New Project where you will get to enter the name of the project.

Enter the project name and click Create. It will take a couple of seconds for the project to be created.

API Activation:

Now that you have created the project, you need to enable the YouTube Data API.

Click Enable APIs and Services in order to enable the necessary API.

Type the word “youtube” in the search  box, then click the card with YouTube Data API v3 text.

Finally, click Enable.

Credentials Setup:

Now that you have enabled the YouTube Data API, you need to setup the necessary credentials.

Click Create Credentials.

In the next page click Cancel. 

Click the OAuth consent screen tab and fill in the application and email address. .

Scroll down and click Save.

Select the Credentials tab, click Create Credentials and select OAuth client ID. 

Select the application type Other, enter the name “YouTube Comment Extractor”, and click the Create button.

Click OK to dismiss the resulting dialog.

Click the file download button (Download JSON) to the right of the client ID.

Finally, move the downloaded file to your working directory and rename it client_secret.json.

Client Installation:

Now that you have setup the credentials to access the API, you need to install the Google API client library. You can do so by running:

pip install google-api-python-client

You need to install additional libraries which will handle authentication

pip install google-auth google-auth-oauthlib google-auth-httplib2
