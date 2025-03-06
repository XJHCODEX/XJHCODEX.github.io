# Exploring Oracle Cloud Services

Discover the features and capabilities of Oracle Cloud, including cloud storage, computing power, and advanced analytics.

## Download Oracle Autonomous Database wallet
## Download Oracle Istant Client for the following operating system

## Configuring Oracle Instant Client
```bash
nano ~/.bashrc

# Add the following lines:
# Replace following paths with proper path of instant client
export LD_LIBRARY_PATH=/home/ubuntu instantclient_23_7:$LD_LIBRARY_PATH
export PATH=/home/ubuntu/instantclient_23_7:$PATH
export TNS_ADMIN="/home/ubuntu/<wallet_name>"

source ~/.bashrc
```

## Open ports on vcn

## Setup IP Forwarding (Optional)
```bash
sudo sysctl net.ipv4.ip_forward
sudo sysctl -w net.ipv4.ip_forward=1
echo "net.ipv4.ip_forward=1" | sudo tee -a /etc/sysctl.conf
sudo sysctl -p
```

## Configure firewall
```bash
sudo ufw status
sudo ufw enable
sudo ufw allow 5001/tcp
sudo ufw reload
```

## Key Takeaways:
- How to set up a cloud environment
- Managing cloud resources efficiently