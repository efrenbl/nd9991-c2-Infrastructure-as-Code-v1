# nd9991-c2-Infrastructure-as-Code-v1
nd9991-c2-Infrastructure-as-Code-v1


### How to run the supporting material?
You can run the supporting material in two easy steps:
```bash
# Ensure that the AWS CLI is configured before runniing the command below
# Create the network infrastructure
# Check the region in the create.sh file
./create.sh myFirstStack network.yml network.json
# Create servers
# Change the AMI ID and key-pair name in the servers.yml
# Check the region in the update.sh file
./create.sh mySecStack servers.yml servers.json
```

### Diagram
![Alt text](udacity.jpeg?raw=true "Diagram")