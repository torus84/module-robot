# Installation
```bash
# Add repository
composer config repositories.torus84-robot git "https://github.com/torus84/module-robot.git"

# Configure minimum-stability
composer config minimum-stability dev

# Adding module
composer require torus84/module-robot:dev-master

# Turning-on/Enabling the module
bin/magento module:enable Torus_Robot \
&& bin/magento setup:upgrade \
&& bin/magento cache:clean
```