500 Internal Server Error:
A Permissions Error. In most cases, a 500 Internal Server Error is due to an incorrect permission on one or more files or folders. In most of those cases, an incorrect permission on a PHP and CGI script is to blame. These should usually be set at 0775 (-rwxr-xr-x).
A PHP Timeout. If your script connects to external resources and those resources timeout, an HTTP 500 error can occur. Timeout rules, or better error handling in your script, should help if this is the cause of the 500 error.
A Coding Error in .htaccess. While not as common, be sure to check that your site's .htaccess file is properly structured.
