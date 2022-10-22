# Defer-macOS-major-upgrade-and-minor-update

Steps to add custom json schema to Jamf Pro
1. Log in to Jamf Pro.
2. Click Computers at the top of the page.
3. Click Configuration Profiles.
4. Click New.
5. Use the General payload to configure basic settings, including the distribution method.
6. Click the Application & Custom Settings payload, and then click Configure.
7. Select Configure Settings for the Creation Method.
8. Choose "Custom Schema" from the Source pop-up menu.
9. Enter the preference domain for your app.
10. Using the JSON Schema for deffering major upgrade / minor update, the preference domain is the following:
com.apple.applicationaccess
11. Copy the JSON Schema of for this GitHub page to the Custom Schema field in Application Properties.
12. To customize the properties using the Jamf Pro interface, click Properties.
13. Jamf Pro displays a list of configurable settings based on the JSON Schema manifest.
14. Add values to the managed keys to customize the app settings.
15. Click the Scope tab and configure the scope of the profile.
16. Click Save.
