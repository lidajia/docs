# docs
store ideas, resources,docs

# debug firewalld
firewall-cmd --set-log-denied=all \
firewall-cmd --reload \
dmesg | grep -i reject 

