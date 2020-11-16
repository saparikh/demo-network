# demo-network

This repository holds the configurations of the network elements (routers, switches, firewalls, etc...) in our demo network.

The purpose is to show off the use of Batfish Enterprise to evaluate policy compliance of production configurations that are archived in Github
- This is accomplished with the help of a custom Github action. 
- You can see how the GH action is leveraged by looking at workflow in .github/workflows/demonet_test.yml in this repository

Network policies are stored in a separate repository, separating control over the network device configurations and network policies.
- Example network policies can be found here https://github.com/saparikh/demo-policies


