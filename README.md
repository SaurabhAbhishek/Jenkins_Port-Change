# Jenkins_Port-Change

sudo nano /etc/default/jenkins

cd /usr/lib/systemd/system/jenkins.service

systemctl daemon-reload


systemctl restart jenkins
