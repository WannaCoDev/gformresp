# GFormResp
# ImpressPages CMS form submissions to Google Sheets

Install the plugin as usual in ImpressPages CMS 

Once installed you need to get a web app apps script url and paste it in the field as indicated in the image

![plugin settings](http://www.wannaco.net/file/2017/05/09/forms_to_sheets_plugin_settings_2.PNG)

To get the Web App running follow these steps:

1. Create or open a spreadsheet in Google Sheets.
2. Select the menu item Tools > Script editor. If you are presented with a welcome screen, click Blank Project on the left to start a new project.
3. Delete any code in the script editor. Copy the code in the appsscript.txt file found in the plugins main direcotry and paste the code into the script editor.
4. Select the menu item File > Save. Give the script project a name and click OK.

# Deploying a script as a web app
## To publish a script as a web app, follow these steps:

![Dialog deploy app](https://developers.google.com/apps-script/images/deploy_web_app.png)

1. Save a new version of the script by selecting File > Manage Versions, then Save New Version.
2. Select Publish > Deploy as web app.
3. Under Project version, select the version you just saved.
4. Under Execute the app as, select whose authorization the app should run with: your account (the developer's).
5. Under Who has access to the app, select who should be allowed to visit it. The options must be "Anyone, even anonymous" (@gmail.com accounts ). 
6. Click Deploy.
Once you click Deploy, you'll see a new dialog with a message indicating that your project has been successfully deployed as a web app.

![Dialog deploy app](https://developers.google.com/apps-script/images/web_app_url.png)


## This dialog provides two important URLs for your app:


The first is labeled Current web app URL and ends in /exec. This URL is for the published version of your app, based on the last version you saved and deployed.
The second is the link labeled latest code and ends in /dev. This URL can only be accessed by users who have edit access to the script. This instance of the app always runs the most recently saved code — not necessarily a formal version — and is intended for quick testing during development.

## All is set and it should now work smoothly as whown in this video. 

[![image](https://cloud.githubusercontent.com/assets/7078331/25797243/9eb89cec-3399-11e7-9538-614b0eff13ba.png)](https://www.youtube.com/watch?v=9375kF84GRc "ImpressPages CMS forms to Google Sheets")
