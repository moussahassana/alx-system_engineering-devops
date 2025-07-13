# 0-block_all_incoming_traffic_but

This script configures a UFW (Uncomplicated Firewall) on an Ubuntu server to **block all incoming traffic**, **except** for the following TCP ports:

- **22** – SSH (for remote access)
- **80** – HTTP (web traffic)
- **443** – HTTPS (secure web traffic)

## 🛠 Usage

Run the script with root privileges or using `sudo`:

```bash
sudo ./0-block_all_incoming_traffic_but

