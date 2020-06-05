# high-availability-app-using-cloudformation
<h3> Udacity Cloud Nanodegree Webapp using AWS Cloudformation stacks </h3>
<br>
stack-1 deploys the network-infrastructure required 

Creates - VPC, Internet Gateway, NAT, Public and Private Subnets and Routes

<br>
stack-2 deploys the server-infrastructure required 

Creates - LoadBalancer, SecurityGroup, Role for s3 download, LaunchConfiguration and WebAppGroup


<h3> Create stacks </h3>

```
./create_stack.sh <stack-1> network.yml network-parameters.json
./create_stack.sh <stack-2> servers.yml server-parameters.json
```

<h3> Update stacks </h3>

```
./update_stack.sh <stack-1> network.yml network-parameters.json
./update_stack.sh <stack-2> servers.yml server-parameters.json
```
