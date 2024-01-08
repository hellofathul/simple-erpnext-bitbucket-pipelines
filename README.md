
# Simple ERPNext Bitbucket Pipeline Configurations with SSHPass

This is a simple bitbucket-pipelines.yml file that I created while learning to implement CI/CD in my ERPNext app. I'm using Ubuntu 22.04.

I didn't use SSH Access Keys since I'll be using the app in a small scale environment, and security isn't a major concern. I'm the only one with access to the repository, so my pipeline variables and their values won't be visible to anyone else.






## Pipeline Variables

Below, you'll find a list of pipeline variables used in this configuration:

`UBUNTU_SSH_PASSWORD`: Password for the Ubuntu user.

`USERNAME`: Your Ubuntu username.

`HOST`: Hostname, domain, or IP address.

`PORT`: Port number.

`APP_NAME`: The name of your custom ERPNext app.

`SITE_NAME`: Your chosen Site Name.

Feel free to change these variables to align with your specific ERPNext project requirements. This configuration is part of my learning journey in CI/CD implementation. Enjoy exploring and coding!