# Checkpoint 7 - Mission Reflection

You must check the host server resources. Containers need hardware so they can work. Even if your app is perfect a host that runs out of memory or disk space will crash all containers running inside it. Monitor the foundation first. This makes sure the server can handle the workloads before you add traffic.

The docker logs command helps you to find the error when users cannot log into web app. You don't need to guess. You just read logs to see if user put the password or if server crash completely. It makes fixing problem faster for the team.

Logs and metrics is doing jobs. Logs are record of events that happens in the system. For example log show when user visit a page or when app throw a 404 error. Metrics measures system health over time like how much CPU or memory the system use. Metrics show when the server is struggle. Logs tells you exactly why it break.

Big companies do not check thousands of containers by hand. They are using tools to monitor everything at once. They use tool called Prometheus for collect data from all servers. Then they use Grafana to build dashboard and send alert when resources gets too high.

My troubleshooting skill, in Linux get better. Before this mission I only deploying apps. Now I checking their health too. I know how find the hardware baseline using command like top and df -h. I feeling confident to use Docker tools to find error and resource spike so I do not have to guess when something break.