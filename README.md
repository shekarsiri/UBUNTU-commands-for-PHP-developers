<h3>Install LAMP server using the TASKSEL</h3>

sudo apt-get install tasksel
tasksel

<h3>Install MCRYPT for PHP5</h3>
sudo apt-get install php5-mcrypt



<h3>Add Site and Chnage Localhost URL</h3>
sudo cp /etc/apache2/sites-available/default /etc/apache2/sites-available/laravel <br/>
sudo gedit /etc/apache2/sites-available/laravel

<h5>Edit the config file as requried</h5>
sudo a2ensite laravel

<h5>Enable the new site</h5>
sudo a2ensite laravel

<h5>Edit host file</h5>
sudo gedit /etc/hosts

<h5>Reload the apache</h5>
sudo /etc/init.d/apache2 reload

<h5>Restart the apache</h5>
sudo /etc/init.d/apache2 restart
