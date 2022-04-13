# 3210 Labs

## Lab instructions

### Initial setup (done once)
1. Download and install Docker Desktop from https://www.docker.com/products/docker-desktop and install any required dependencies asked for.

2.  Create a folder on your local system.  We suggest naming it "3210_labs" and putting in your home folder.

### Immediately prior to running a lab
1.  Open Powershell if using Windows or terminal if using a Mac, and navigate to the folder you created for use in this lab.
2.  Use the *curl* command to download the "raw" version of the script to use for the lab you want to run.  You will need the URL provided when you click the "Raw" button on the particular script you want to download.
  - If you are in Powershell, type `curl <URL> -OutFile <filename>`, e.g. `curl https://raw.githubusercontent.com/AndyGreenPhD/ksu_docker_labs/main/3210/3210.yml -OutFile 3210.yml`
  - If you are in a Mac terminal, type `curl <URL> -o <filename>`, e.g. `curl https://raw.githubusercontent.com/AndyGreenPhD/ksu_docker_labs/main/3210/3210.yml -o 3210.yml`
3.  Type `docker-compose -f <filename> -p 3210_lab up -d` where filename is the name of the script you downloaded
4.  Complete the lab


### Immediately after completing the lab
1.  Delete the container(s) and image(s) to clean up your environment
