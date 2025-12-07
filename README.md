# ansible-assignment-2
Ansible Playbook Assignment 2 for CNIT-381

## Description of Playbook
The following playbook will configure the three loopback interfaces on each router. Next, EIGRP will be configured under Autonomous System 100. All networks, including loopbacks and the management network will be advertised in EIGRP. Lastly, verification will be performed by outputting the EIGRP neighbors and loopback interfaces. 

## Instructions to Run
Run the following command: ```ansible-playbook -i inventory.ini assignment2.yaml```

## Screenshot of Successful Execution
### Successful Playbook Execution
![Screenshot showing successful execution.](screenshots/execution.png)

### Output of show ip interface brief
#### Core-Router-East
![Screenshot of Core-Router-East ip interfaces.](screenshots/core-router-east-interfaces.png)
#### Core-Router-West
![Screenshot of Core-Router-West ip interfaces.](screenshots/core-router-west-interfaces.png)

### Output of show ip eigrp neighbors
#### Core-Router-East
![Screenshot of Core-Router-East EIGRP neighbors.](screenshots/core-router-east-eigrp.png)
#### Core-Router-West
![Screenshot of Core-Router-West EIGRP neighbors.](screenshots/core-router-west-eigrp.png)