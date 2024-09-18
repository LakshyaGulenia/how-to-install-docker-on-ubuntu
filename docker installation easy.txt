

# How to Install Docker on Ubuntu

## Step 1: Verify Ubuntu Version

First, ensure you are running the latest version of Ubuntu for a smooth installation. To check your Ubuntu version, run the following command:


lsb_release -a


## Step 2: Update Package Database

Update your package database to ensure you have the latest package information. Run the following command:


sudo apt-get update


You will need to enter your Ubuntu password to proceed.

## Step 3: Install Docker Engine

To install the Docker Engine, execute the following command:


sudo apt install docker.io


When prompted, type "Y" and press Enter. This command will download and install the Docker package.

## Step 4: Enable Docker Service

After installing Docker, enable the Docker service with the following command:


sudo systemctl enable docker


## Step 5: Verify Docker is Running

Ensure Docker is running by checking its status:


sudo systemctl status docker


If everything is set up correctly, you should see that Docker is running.

## Step 6: Test Docker Installation

To test if Docker is installed and working correctly, run the following command:


sudo docker run hello-world


If everything is set up correctly, you should see the message "Hello from Docker."

