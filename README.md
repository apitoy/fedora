# fedora
Install on feodra


## groovy

https://snapcraft.io/install/groovy/fedora


### Enable snapd

    sudo dnf install snapd


### Either log out and back in again, or restart your system, to ensure snap’s paths are updated correctly.
### To enable classic snap support, enter the following to create a symbolic link between /var/lib/snapd/snap and /snap:

    sudo ln -s /var/lib/snapd/snap /snap

## Install Apache Groovy Programming Language

sudo snap install groovy --classic



## kamel

https://camel.apache.org/camel-k/1.8.x/languages/groovy.html

kamel run helloworld.groovy --dev
