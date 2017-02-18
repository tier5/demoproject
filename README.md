# demoproject

    Make sure Vagrant is installed locally and works.. In case you get an error and it tells you to change enable hardware virtualization technology (VT-x) , then just enable it from BIOS.
    Clone Repo --> https://github.com/tier5/demoproject
    Then run this command --> vagrant box add ubuntu.16.04 https://cloud-images.ubuntu.com/xenial/current/xenial-server-cloudimg-amd64-vagrant.box
    Then Do --> vagrant up
    Then Do --> vagrant ssh
    Then Do --> cd /var/www/html/scripts
    Then Do --> sudo ./after_launch_script ( Make sure local mysql password should be toor )
    Then Local Environment Can be Seen at --> http://127.0.0.1:2002/index
                                
