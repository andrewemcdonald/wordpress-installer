This script installs the latest version of wordpress on a debian linux machine.

Instructions:

If you don't already have git installed, open you bash terminal and type:

sudo apt install git

To download and run the script, open your bash terminal and type:

git clone https://github.com/andrewemcdonald/wordpress-installer.git
sudo bash wordpress-installer/wp_install

The second command should start the script. As the script runs, the terminal will occasionally
ask if you approve of certain installations. If you trust me, press "y", then press enter,
and the machine will install those packages.

![Alt text](/screenshots/yes_or_no.png?raw=true "Hit yes, then enter.")

phpmyadmin will ask you to confirm some settings. All of the defaults work fine, so press
enter when prompted.

![Alt text](/screenshots/php_configure_one.png?raw=true "Hit enter.")
![Alt text](/screenshots/php_configure_two.png?raw=true "Hit enter.")
![Alt text](/screenshots/php_configure_three.png?raw=true "Hit enter.")
