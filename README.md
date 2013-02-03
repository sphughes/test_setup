test_setup
==========

This allows you to test your client side configuration.

It's quite  simple to do really.

git config --global user.name 'User Name'

git config --global user.email 'your.email@somehost.com'

mkdir github

cd github

git clone https://github.com/sphughes/test_setup.git

git remote set-url origin https://sphughes@github.com/sphughes/test_setup.git

*(SSH version) git remote set-url origin ssh://git@github.com/sphughes/test_setup.git*

*(Used for ssh) git config --global credential.helper 'cache --timeout=7200'*


