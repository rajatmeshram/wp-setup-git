# Setup git project in Ubantu or Mac and Window

How to Setup github project in Your System

<h4>Step:1 Login your Github Account ( <a href="https://gitlab.letschbang.com/users/sign_in">Click Here</a> ).</h4>

<img src="http://php71.indianic.com/ritikakankani/image/SigninGitLab.png" />

<hr>

<h4> Step:2 See Your Project List here. Select your Project ( Click to your project )</h4>

<img src="http://php71.indianic.com/ritikakankani/image/ProjectsDashboardGitLab.png" />

<hr>

<h4> Step:3 Click to "Clone" button and copy to git project URL for Setup this project</h4>

<img src="http://php71.indianic.com/ritikakankani/image/ritikakankaniwebwp.png" />

<hr>

<h4> Step:4 Open your terminal</h4>

<img src="http://php71.indianic.com/ritikakankani/image/terminal.png" />

<hr>

<h4> Step:5 Follow Below Commans</h4>
<code>
<p>cd 'SELECT YOUR PATH FROM HTDOCS' </p>
<p>Ex: cd /opt/lampp/htdocs </p>
<br>
</code>
<img src="http://php71.indianic.com/ritikakankani/image/terminal_1.png" />
<hr>
<h4> Step:6 What you have copied is to take the clone here </h4>
<code>
<p> Syntax: git clone "Your Copy URL" Project_name </p>
  <p> Example: git clone http://git.indianic.com/ritikakankani/web-wp.git ritikakankani</p>
  <br>
</code>
<img src="http://php71.indianic.com/ritikakankani/image/terminal_2.gif" />
<hr>
<p>- Enter Your git username and Password</p>
<br>
<img src="http://php71.indianic.com/ritikakankani/image/terminal_3.png" />
<hr>
<p>- Goto the project directory </p>
<p> cd ritikakankani/ </p>
<br>
<img src="http://php71.indianic.com/ritikakankani/image/terminal_4.png" />
<hr>
<p>- Create Readme file </p>
<p> Example: touch README.md </p>
<br>
<img src="http://php71.indianic.com/ritikakankani/image/terminal_5.png" />
<hr>
<p>- Create .gitignore file. And Copy & paste below code in .gitignore file </p>
<pre> 
### WordPress ###
*.log
wp-config.php
wp-content/advanced-cache.php
wp-content/backup-db/
wp-content/backups/
wp-content/blogs.dir/
wp-content/cache/
wp-content/upgrade/
wp-content/uploads/
wp-content/mu-plugins/
wp-content/wp-cache-config.php
wp-content/plugins/hello.php

/.htaccess
/license.txt
/readme.html
/sitemap.xml
/sitemap.xml.gz </pre>
<br>
<img src="http://php71.indianic.com/ritikakankani/image/folder.png" />
<hr>
<p>- Code push in Master branch </p>
<p> Step 1: <b>git add .</b> </p>
<p> Step 2: <b>git commit -m "add README and all code push on Master branch"</b> </p>
<p> Step 3: <b>git push -u origin master</b> </p>
<br>
<img src="http://php71.indianic.com/ritikakankani/image/terminal_6.png" />
<hr>
<p>- Create staging branch </p>
<p> Step 1: <b>git checkout -b staging</b> </p>
<p> Step 2: <b>git branch</b></p>
<br>
<img src="http://php71.indianic.com/ritikakankani/image/terminal_7.png" />
<br>
<p> Step 3: <b>Copy your WordPress Project OR Wordpress Extract here</b> </p>
<br>
<img src="http://php71.indianic.com/ritikakankani/image/folder_2.png" />
<br>
<p> Step 4: <b>git add .</b> </p>
<p> Step 5: <b>git commit -m "First code commit"</b> </p>
<p> Step 6: <b>git push origin staging</b> </p>
<br>
<img src="http://php71.indianic.com/ritikakankani/image/terminal_8.png" />
<hr>
<p>- Create Your branch </p>
<p> Step 1: <b>git checkout -b dev_rajat</b> </p>
<p> Step 2: <b>git branch</b></p>
<img src="http://php71.indianic.com/ritikakankani/image/terminal_9.png" />
<p> Step 3: <b>ls</b></p>
<img src="http://php71.indianic.com/ritikakankani/image/ls.png" />

# Project setup done 
