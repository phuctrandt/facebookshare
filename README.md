#FacebookShare plugin

Thank you for choosing FacebookShare plugin. If you are reading this I am sure that you have great interests toward Facebook and Wordpress integration.

This Wordpress plugin helps your everyday posting work become easier. With FacebookShare plugin, you can share a full post, or a full post with an image or even just sharing a link leading to your page. 

## Server Setup Instruction

Should you ignore this step, you won't be able to retrieve Facebook App token, and you would experience a non-critical error when creating new post.

1. You need php5-curl extension to run this plugin. Install by `sudo apt-get install php5-curl`
2. Enable the extension by `sudo php5enmod curl`
3. Restart Apache by `service apache2 restart` (similar for other web platform).

## Plugin Setup instruction:
1. Upload this plugin to plugins folder (www.yoursite.com/wp-content/plugins)
2. Enable this plugin under Plugins section in Admin Panel and a new FacebookShare setting page will appear
3.  In FacebookShare setting, you can fill in basic information about your Page. Remember this must be the page you have admin right. If you have not got a facebook app yet, heading to https://developers.facebook.com and register one web app there. Remember in app settings, put your website URL to the Site URL fields.
4.  If you don’t know your facebook page ID, then head to http://findmyfacebookid.com and find your own one.
5.  Fill in App ID and App Secret you obtained from the Facebook app.
6.  Save the settings first.
7.  Click on “here” in Facebook app token row. Then the token will be fetched to your site
8.  Save the settings again
9.  The site is now ready to use. Have a productive day!

This is my first Wordpress plugin, it will probably have many bugs. Please email me at **me (at) lazystudentblog.com**, I would be very pleased to receive your feedback
