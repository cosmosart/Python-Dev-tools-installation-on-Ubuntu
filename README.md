# Setting up an Apache Spark environment from scratch.
    * This class will use python3 not python2.
    * The easiest way to install everything is to use the Docker instance that we provide. 
      If for whatever reason, you cannot install Docker 
      then we also provide instructions to download and install the required Python implementation 
      and associated libaries.
    * There are software installation directions on the course page

### 1. For Ubuntu Users
If you don't have any experience with apache spark setup, highly recommend using Ubuntu for this course.

 * Firstly, update and upgrade OS
     sudo apt update && sudo apt upgrade -y 
 * Install python3, pip and upgrade
    > sudo apt-get -y install python3 python3-pip
    > sudo pip3 install --upgrade pip
 * Install jupyter notebook
    > pip3 install jupyter
