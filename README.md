# kubernetes-pihole-example
Example deployment config for kubernetes to run pihole containers

Update hostAliases section with hostnames for your network to have the DNS resolve the correct IPs.

Update value under WEBPASSWD to define the web interface admin password, or remove to be random and it will appear in the logs.

Update value under TZ with correct timezone for your pihole.

Apply with "kubectl apply -f pihole.yml" and then expose however you want.
