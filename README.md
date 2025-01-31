<h1 align="center"/>⚡️ Welcome to XUI Panel Subscription Template ⚡️</h1>

> ** This is a custom subscription template designed for the XUI Panel, providing a clear view of service details, including usage, expiration date, and more. 

**We don't need financial support, only Star (⭐) is enough, thank you.**


## Install & Upgrade

```
bash <(curl -Ls https://raw.githubusercontent.com/SalehGfx/xui-subscription-template/refs/heads/master/main.sh )
```

## Configuration File
```
nano /opt/DVHOST/dvhost.config
```
You must restart the service after changing the configuration file.
```
systemctl restart DVHOST_TEMPLATE
systemctl status DVHOST_TEMPLATE
```
**You should not have ports 2082 and 2083 involved.**


## 🪚 Preview
<p align="left">
    <img width="100%" src="https://github.com/user-attachments/assets/629f455d-58c8-4b9b-b722-2948b39a9511" alt="Image">
</p>


## Languages

- English

## Dynamic Variables
The template uses the following dynamic variables to display user-specific information:

| Variable                | Description                        |
|-------------------------|------------------------------------|
| `<%= data.id %>`        | User or subscription ID.           |
| `<%= data.email %>`     | User's email address.              |
| `<%= data.suburl %>`    | Subscription URL.                  |
| `<%= data.enable %>`    | Subscription status (true/false).  |
| `<%= data.up %>`        | Uploaded data (bytes).             |
| `<%= data.down %>`      | Downloaded data (bytes).           |
| `<%= data.total %>`     | Total allowed data (bytes).        |
| `<%= data.expiryTime %>`| Expiration time (timestamp).       |
| `<%= data.inboundId %>` | Inbound connection ID.             |

Enjoy seamless and user-friendly subscription management with this template!



