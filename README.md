# HomeLab

Here i will be documenting my homelab experience, if anyone has questions or tips feel free to message me on discord: pytho_
<br>
<br>
<br>
<br>
# Homelab Diagram
<img width="712" height="741" alt="diagram drawio" src="https://github.com/user-attachments/assets/bb35ccdd-f16a-4a2b-9e5e-4d4c1d87c967" />

# Info
## Wazuh

I installed Wazuh on Ubuntu, installing ubuntu on VM is simple so i wont show it here. 


After you install Ubuntu just paste this command: ```curl -sO https://packages.wazuh.com/4.12/wazuh-install.sh && sudo bash ./wazuh-install.sh -a``` it will install Wazuh and display login and password for your admin account.

To see Wazuh dashboard just type your IP in the browser


After that you will need to install ***Wazuh Agent*** on other machines that you want to collect logs from.

You need to click Deploy new agent on the Wazuh dashboard, and it will write you exact commands that you need to paste to install agents. **Its that simple.**

---
