# Cyclonedds
Build and play with cyclonedds

# Tasks avaialble
1.  Create cyclonedds image
2.  Run helloworld example
3.  Remove helloworld example
4.  Start wireshark monitoring

# Getting Started

## Fetch cyclonedds image
VS code task is available to create an image with cyclonedds. Click `F1` , select command `Tasks: Run Task` , select 
`Create cyclonedds image` and `Continue without scanning the output`.

## Start wireshark monitor
Start wireshark container to snoop the docker traffic. Click `F1` , select command `Tasks: Run Task` , select 
`Start wireshark monitoring` and `Continue without scanning the output`.

Open VS Code in build browser to see the wireshark log.
Press `F1` Enter `Simple Browser:Show` enter the address `http:\\localhost:3000`

Select the interface to monitor based network subnet in the `docker-compose.yml`file.
![image](https://media.github.boschdevcloud.com/user/6658/files/8bedfb48-bda6-4d52-bd89-fbd367bc3059)

## Start helloworld example
helloworld example binaries are already build in the image file. Executing the task `Run Helloworld example` creates two machines , one publisher and one subsciber. Refer `docker-compose.yml` for details.

## Stopping containers
The running taks can be closed by calling the corresponding Stop tasks
`Stop wireshark monitoring`
`Remove Helloworld example`
