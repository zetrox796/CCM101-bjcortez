# Checkpoint 7 - Mission Reflect

A Docker container starts in a few seconds because it uses the same operating system that lives on the host machine. A Virtual Machine takes a longer time to start because it must install a whole new guest operating system. You must give a Machine a lot of memory. A Docker container saves time. Uses far fewer system resources. This speed change how we put applications into production.

Port mapping is what connects the host computer to the Docker container. The command "-p 8080:80" links the host port 8080 to the Docker container port 80. The Docker container runs in its network, which blocks outside traffic by default. Without port mapping traffic from outside cannot reach the web server and users will see a connection. Port mapping opens one door for web traffic.

The "docker rm" command deletes a stopped Docker container completely. This action removes all data that lived inside that Docker container. The Docker container throws away every change that happened while it was running. Any new files you created inside that Docker container are lost. You must save data to a permanent host volume. A host volume keeps data safe even after you remove that Docker container.

Docker containers help software developers and IT teams work together better. Developers write code inside a Docker container. IT teams run that same Docker container, on the production server, which stops the common problem where code fails on different computers. Both teams use the environment. They deploy software faster. Make fewer errors during deployment.

After completing more laboratory activities, my Github portfolio now shows a wider range of skills. Now it even show more skills i learned after completing the latest activity.