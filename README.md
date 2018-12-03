This script installs the latest version of wordpress on a debian linux machine.

Instructions:

If you don't already have git installed, open you bash terminal and type:

sudo apt install git

To download and run the script, open your bash terminal and type:

git clone https://github.com/andrewemcdonald/wordpress-installer.git

sudo bash wordpress-installer/wp_install

The second command should start the script. As the script runs, the terminal will occasionally ask if you approve of certain installations. If you trust me, press "y", then press enter, and the machine will install those packages.

![Alt text](/screenshots/yes_or_no.png?raw=true "Hit yes, then enter.")

phpmyadmin will ask you to confirm some settings. All of the defaults work fine, so press
enter when prompted.

![Alt text](/screenshots/php_configure_one.png?raw=true "Hit enter.")
![Alt text](/screenshots/php_configure_two.png?raw=true "Hit enter.")
![Alt text](/screenshots/php_configure_three.png?raw=true "Hit enter.")

After the installation script is finished running, type the IP address of your site server and you should get the following page:

![Alt text](/screenshots/wordpress_configure_one.png?raw=true "Hit Let's Go!.")

Press the "Let's Go!" button. The next page will prompt you for some site information. In the "username" field, replace the default text with "webmaster", then press submit. 

![Alt text](/screenshots/wordpress_configure_two.png?raw=true "Enter information and press submit.")

After you submit the information, wordpress will ask for credential information for the main site administrator. Fill this out however you see fit, then press Install Wordpress, and you should be all set!

![Alt text](/screenshots/wordpress_configure_three.png?raw=true "Fill out however you see fit.")

I also highly recommend changing the password for the SQL webmaster admin. To do this, in the search bar type the IP address of you server, follwed by "/phpmyadmin". You will be prompted for a username and password. The username is "webmaster" and the password is "password". Once logged in, in the main dashboard under general settings, there will be a link to "change password". Click the link and type in a new password.

