# CDN_Data
https://stackoverflow.com/questions/4923253/hosting-your-own-javascript-scripts-files-other-than-jquery-on-fast-free-cdns

The above link shows how to host a JS file as a CDN for free.

jsdelivr (https://www.jsdelivr.com/) is a free, fast and reliable service to host your javascript files on a CDN.
The file should be on github repository first, then use the following format to use the CDN:-

https://cdn.jsdelivr.net/gh/user/repo@version/file
In the above format replace user with your username on github, repo with repository name and version with the version of your repository
You can use this CDN service for hosted anywhere like npmjs.com or even on your wordpress sites using their plugin.
Please visit the website for more information and to know how it works.

FOR OUR SPECFIC CASE:

https://cdn.jsdelivr.net/gh/gazingstocks/CDN_Data/Data_SDOG_Daily_1.js
<p>the old url was</p>
https://cdn.jsdelivr.net/gh/rguptaaccountcontrol/CDN_Data/Data_SDOG_Daily_1.js 
<p>

In the above format replace user with your username on github, repo with repository name and version with the version of your repository
You can use this CDN service for hosted anywhere like npmjs.com or even on your wordpress sites using their plugin.
Please visit the website for more information and to know how it works.

The Data_SDOG_Daily_1.js file has only javascript code and syntax. It does not have html tags like <script>. If we put html tags or any syntax which is not javascript, the link to CDN does not work.

OTHER LINKS TO READ:
https://www.khanacademy.org/computing/computer-programming/html-css/web-development-tools/a/hosting-your-website-on-github

Google drive does not allow to host files and use them ad CDN anymore.
