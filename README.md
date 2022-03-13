# Contacts-Management-App
Contacts app is an app which shows the contacts stored in the database if a user Signin and add a new contact.

<h1>Getting Started</h1>
<p>These instructions will get you a copy of the project up and running on your local machine for testing purposes.</p>

<h2>Prerequisites</h2>
<code>python== 3.6 or up and django==2.0 or up</code>

<h2>Downloading</h2>
<pre>open the below url and download the contactsapp.zip file and extract it in your system</pre>
<code>git clone https://github.com/bhargavnag/Contacts-Management-App/blob/main/Contacts.zip</code><br><br>

<h2>Install the visual studio in your local system using the link</h2>
<code>https://code.visualstudio.com/</code>

<h2>Open the Extracted folder</h2>
<p>Now open the command prompt by entering cmd</p>
<p>Now activate the environment by using below command</p>
<code>myvenv\Scripts\activate</p>
<p>When it is successfully activated.Open the code by entering the command</p>
<code>code .</code>

<h2>Installing Xampp control</h2>
<p>Now install xampp control panel using the link</p>
<code>https://www.apachefriends.org/download.html</code>

<h2>To use admin panel you need to create superuser using this command </h2>
<code>python manage.py createsuperuser</code>

<h2>Creating database</h2>
<p>Open the Xampp Control Panel and start the apache and mysql and click on admin button beside mysql,it opens an admin panel</p>
<p>Now open the settings.py file in the projects folder and goto line number 80 copy the name of the database and create a database with the same name in the admin panel</p>

<h2>Migrations</h2>
<p>Now open the command prompt and enter the below command to migrate</p>
<code>python manage.py migrate</code>

<p>To run the program in local server use the following command</p>
<code>python manage.py runserver</code>
<p>Then goto http://127.0.0.1:8000/ in your browser</p>

<h1>===THANK YOU===</h1>
