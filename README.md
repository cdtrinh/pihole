# pihole


IFTTT Applets
-------------
Block the Internet

UnBlock the Internet


Pi-hole Webhook URI's
----------------
Block:  http://FQDN:9999/hooks/pihole-block

Unblock:  http://FQDN:9999/hooks/pihole-unblock


Linux Setup (Ubuntu)
--------------------
Install Pihole: https://docs.pi-hole.net/main/basic-install/

Install webhook package from apt: sudo apt-get install webhook

Clone pihole-webhook repo to the following directory /apps/webhook/

Create Webhook Service:  /etc/systemd/system/webhooks.service



