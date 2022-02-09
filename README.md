# pihole


IFTTT
-----
Block the Internet

UnBlock the Internet


Pi-hole webhooks
----------------
http://FQDN:9999/hooks/pihole-block

http://FQDN:9999/hooks/pihole-unblock


Linux Setup (Ubuntu)
--------------------
Install webhook package from apt: sudo apt-get install webhook

Create Webhook Service:  /etc/systemd/system/webhooks.service


Webhook App
-----------
sudo apt install webhook

/apps/webhook/: Webhook config and block/unblock scripts


