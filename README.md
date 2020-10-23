# Send-Mail-using-Gmail-Api

## Steps for execution:
### Step1:
 Turn on the Gmail API[Tutorial is given in Buttom]
### Step 2:
Install the googleAPI 
Run the following commands to install the libraries using npm:
```sh
$ npm install googleapis@39 --save
```
### Step 3:
Execute the File index.js
```sh
$ node .
```
# How to enable gmail API
### Step 1:Create a project at Google API Console
If you want to have access to your Gmail from your mobile or web app, you should start with [Google Developers Console](https://console.developers.google.com/). Those who visit this page for the first time ever will have to agree with the Terms of Service and pick their Country of residence. Then click Select a project and create a new one.Name your new project and press Create at the bottom. 
### Step 2:Enable Gmail API
Once that’s done, you can press the Library tab on the left and find yourself in the API Library page. Enter “Gmail API” in the search bar and click on it once found. Now, you need to enable the API for your project. 
### Step 3:Credentials and authentication with OAuth 2.0
Once the API is enabled, you’ll be taken to a nice dashboard that says, “To use this API, you may need credentials”. If you click Create credentials, you’ll have to pass through a set of questions to find out what kind of credentials you need. We advise you to go another way since we already know what it is: OAuth client ID. So, click the Credential tab on the left, and then pick OAuth client ID from the drop-down list of the Create Credentials button. 

You’ll see the Configure consent screen button. It will bring you to a page with many fields. You can just enter the name of your app and specify authorized domains. Fill in other fields if you want. 

Click save and then pick the type of your app (web app, Android, Chrome App, iOS, or other). After that, name your OAuth Client ID. Also, enter JavaScript origins and redirect domains for use with requests from a browser or a web server respectively. Click create to finalize. That’s it. Download a JSON file with your credentials(credentials.json) – you’ll need it in the main File.

   


### Installation[How to run it]

Application requires [Node.js](https://nodejs.org/) v4+ to run.

Install the dependencies and devDependencies and start the server.

```sh
$ cd quickworkAssessment
$ npm install 
$ node .
```
