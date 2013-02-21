<h3>Install LAMP server using the TASKSEL</h3>
<pre>
sudo apt-get install tasksel
tasksel
</pre>

<hr/>
<h3>Install MCRYPT for PHP5</h3>
<pre>
sudo apt-get install php5-mcrypt
</pre>
<hr/>


<h3>Add Site and Chnage Localhost URL</h3>
<pre>
sudo cp /etc/apache2/sites-available/default /etc/apache2/sites-available/laravel <br/>
sudo gedit /etc/apache2/sites-available/laravel
</pre>

<b>Edit the config file as requried</b>
<pre>
sudo a2ensite laravel
</pre>

<b>Enable the new site</b>
<pre>
sudo a2ensite laravel
</pre>

<b>Edit host file</b>
<pre>
sudo gedit /etc/hosts
</pre>

<b>Reload the apache</b>
<pre>
sudo /etc/init.d/apache2 reload
</pre>

<b>Restart the apache</b>
<pre>
sudo /etc/init.d/apache2 restart
</pre>

<hr/>

<h3>Install CURL</h3>
<pre>
sudo apt-get install curl
</pre>

<hr/>

<h3>Install GIT</h3>
<pre>
sudo apt-get install git
</pre>

<hr/>

<h3>Install COMPOSER and set to global</h3>
<pre>
curl -sS https://getcomposer.org/installer | php <br/>
sudo mv composer.phar /usr/local/bin/composer
</pre>

<hr/>

<h3>Enable apache module mod_rewrite</h3>
<pre>
sudo a2enmod rewrite
</pre>
