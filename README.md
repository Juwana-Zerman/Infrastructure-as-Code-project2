## Udacity Cloud DevOps Infrastructure as Code - Project 2

This project project purpose was to deploy infractructure as code to AWS. The project uses scripts to launch Cloudformation stacks to deploy an autoscaling app to the AWS Cloud.

### Link to DNS URL

[Click Here](http://udaci-WebAp-L8EH7XN7D1QE-1645863624.us-east-1.elb.amazonaws.com)

### Deployment

The stack was deployed using:
`./create.sh udacityproject2dwap network.yml network-parameters.json`
`./create.sh udacityproject2servers servers.yml servers-parameters.json`

Once completed the stacks were deleted using:
`./delete.sh udacityproject2servers servers.yml servers-parameters.json`
`./delete.sh udacityproject2dwap network.yml network-parameters.json`



### Dependencies
* AWS account
* Lucid Chart [www.lucidchart.com](www.lucidchart.com) - Architecture diagram
* VS Code
* Bash
* YAML
* JSON
