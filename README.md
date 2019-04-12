## Setting up credential in jenkins

#Inside JENKINS_HOME use a profile stored in ~/.azure/credentials.

[default]
subscription_id=
client_id=
secret=
tenant=
cert_validation_mode=validate

See anisble documentation to set up this authorization
https://docs.ansible.com/ansible/latest/scenario_guides/guide_azure.html

Also see this youtube video to find out those keys
https://www.youtube.com/watch?v=WygwzN9FfMQ

Note: Azure following the concept of APP's and Resourcegroup to create any number of resources and services in the cloud.

