# Checkpoint 6 - Technical Documentation

**Commands Used:**
* Allow SSH: `sudo ufw allow ssh`
* Default Deny Policy: `sudo ufw default deny incoming` and `sudo ufw default allow outgoing`
* Allow Port 8080: `sudo ufw allow 8080/tcp`

**Explanation:**
If I enable UFW before allowing SSH, the firewall blocks my connection. I will lock myself out of the server.