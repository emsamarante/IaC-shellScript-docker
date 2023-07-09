# IaC: building infrastructure Docker with Shell Script

In this project I set all infrastructure with Docker containers using Shell Script.
This infrastructure will be used in the futher projects envolving data engineering and data analysis.

The infrastructure is compound by two containers Docker in the same networking:
node1: is a ubuntu machine used to extract data from internet, make transformation and load in another container.
node2: is a MySQL container running in the same networking that listen in 3307 (localhost) and 3306 in docker container.

Some packages were installed in node1, such as, curl, lynx, nano, vim and sudo.


![Architecture](https://github.com/emsamarante/IaC-shellScript-docker/tree/main/IacWithShellScript.png)