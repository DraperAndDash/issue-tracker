# issue-tracker

<h2>About</h2>
<p>
	This is the Draper & Dash Issue Tracker. It is used as a plugin that allows D&D QlikView applications to have an issue tracking ability for capturing comments from users and posting them to Basecamp, all within the front end application.
</p>

<h2>How To Install</h2>
<p>
	To add the Issue Tracker Plugin to a QlikView application you need to download this full repository and unzip to the local machine where the applications are. Once you've downloaded this run the file issue-tracker\BSP\Issue Tracker Plugin.vbs and follow the installation instructions.
</p>
<p>
	Welcome to the Issue Tracker Plugin installation wizard!

	This will add the Issue Tracker Plugin to the requested sheets in your QlikView application enabling users to leave comments to Basecamp.

	To ensure the plugin can be installed please make sure your QlikView application is in the following state.
		1. The application is unlocked" + vbNewLine
		2. There is no PRJ folder for the application" + vbNewLine
		3. You have set the Module security settings to allow all access (Ctrl + M)
		4. You haven't added the Issue Tracker Plugin to the application previously

	NB. Make sure QlikView is open but no Edit scripts or other windows are open within it. If the application haults you may need to go to the QlikView window to help it along.
	NB. It is wise to take a backup of the application before starting this installation you can revert back to." + vbNewLine + vbNewLine
</p>

<h2>Basecamp Config</h2>
<p>
	The Issue Tracker Plugin needs a configuration file setup for each project on Basecamp. This consists of the Project and Post IDs needed to post the messages from the app using the Basecamp Classic API. When the Issue Tracker Plugin has been installed in an application then the Load Script must be edited to point to the correct Basecamp-config file. If you cannot find the correct project configuration file then please speak to Dylan.
</p>

<p>
The Draper & Dash Issue Tracker Plugin © uses the following repositories:
	https://github.com/mindspank/qvutils
	https://github.com/basecamp/basecamp-classic-api
</p>