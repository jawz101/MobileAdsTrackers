# MobileAdsTrackers
a slimmed down ad blocklist for Android

direct link

https://raw.githubusercontent.com/jawz101/MobileAdsTrackers/refs/heads/main/hosts.txt

I used to maintain a list called MobileAdsTrackers.  Later, I took up maintaining the Adaway blocklist as it had stagnated and the mobile ads and analytics ecosystem had rapidly evolved in the mid 2010's.  Since then, many ad companies have shut down or been bought by bigger companies and there really are not as many relevant domains.

This list is meant to block domains that are only used by mobile apps.

Step 1:
Remove web browsing noise:
Install a browser that has an ad blocker.  e.g. Firefox for Android + uBlock Origin or Chrome + DNS over HTTPS pointing to a pi-Hole, NextDNS or something.

Step 2:
Use Android's Private DNS feature and point it to a DNS over TLS server or use a VPN-based ad blocker.  Thiiiis list is for that traffic.  Your browser blocks at the browser level and this only needs stuff to block ads in the rest of your apps.


I also want to only keep domains that are still relevant- so I occasionally download Cisco Umbrella's Top 1 Million list and remove any on this list not seen on that list.
