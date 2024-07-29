# Hiding ACF in Production Mode with Bedrock and Sage by Roots.io

## Description:

This repository contains a code snippet for WordPress, specifically tailored for those using the Bedrock and Sage frameworks by Roots.io. The snippet removes the ACF menu from the admin sidebar and admin bar, and restricts direct access to ACF pages when in production mode. This is useful for securing custom field management and preventing changes in the production environment.

### Features:

	•	Removes the ACF menu from the admin sidebar in production mode.
	•	Removes the ACF menu from the admin bar in production mode.
	•	Blocks direct access to ACF pages in production mode.

### Important Note:
This guide assumes you are using Bedrock and Sage by Roots.io, which leverages environment variables for configuration.

### Usage:
#### 1.	Add Environment Variable:
Ensure the WP_ENV environment variable is set to production in your .env file (commonly used with Bedrock):

WP_ENV='production'

#### 2.	Add Code Snippet:
Add the following code to your theme’s functions.php file (in Sage, this file is typically located in app/setup.php) or to a custom plugin.


#WordPress #Advanced Custom Fields #ACF #Bedrock #Sage #Roots.io #Production Mode #WordPress Security #WordPress Customization #Environment Variables
