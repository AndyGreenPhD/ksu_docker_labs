# 3210 Labs

## Lab instructions

### Initial setup (done once)
1. Download and install Docker Desktop from https://www.docker.com/products/docker-desktop and install any required dependencies asked for.

2.  Create a folder on your local system.  We suggest naming it "3210_labs" and putting in your home folder.

### Immediately prior to running a lab
1.  Use a web browser to visit https://github.com/AndyGreenPhD/ksu_docker_labs/3210
2.  Download the script for the lab you are running and save it into the folder you created above.  Save it with the full filename as shown in Github.  NOTE:  This script may change between labs, so always save a fresh copy before beginning a lab.
3.  Open Powershell if using Windows or terminal if using a Mac, and navigate to the folder
4.  Type `docker-compose -f <filename> -p 3210_lab up -d` where filename is the name of the script you downloaded
5.  Complete the lab


### Immediately after completing the lab
1.  Delete the container to clean up your environment
