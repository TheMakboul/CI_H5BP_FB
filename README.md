CI_H5BP_FB
==========

Overview: 
=========
This repo contains the structure for a basic Facebook app built using CI (CodeIgniter v2.1.2), Facebook PHP SDK (v.3.2.0) and H5BP (html5 boilerplate v4.0.0). Feel free to clone and begin using.

Descripton:
===========
A decent starting point for a new Facebook application using CodeIgniter v2.1.2, Facebook PHP SDK (v.3.2.0) and H5BP (html5 boilerplate v4.0.0)

WHAT YOU SHOULD KNOW:
1- 'index.php' is removed from the URL using public_html/.htaccess
2- The base url is set to an empty string in application/config/config.php //$config['base_url']	= '';
3- The default controller is set to application/controllers/h5bp.php in application/config/routes.php //$route['default_controller'] = "h5bp";
4- The file index.php for CI is under public_html/ and the variables $system_path and $application_folder are updated to reference application/ and system/ properly
5- The folder public_html/ is what needs to be web accessible 
6- The folder user_guide/ is removed from CI 2.1.2

WHAT YOU SHOULD DO:
1- After creating your FB app, update application/config/facebook.php to use your appId and secret
2- Let me know if something is not working or needs clarification
3- Enjoy

NOTE:
=====
If code completion is working in your IDE, then you're golden. If not another repo exists containing CodeIgniter v2.1.2 with extra vars added which will make code completion work for CI and the Facebook SDK, just added it to the buildpath for this project.
REPO: https://github.com/TheMakboul/CI_BASE