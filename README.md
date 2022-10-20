# ssh-tunnel-as-systemd

vim /etc/systemd/system/ssh_remote_access.service
systemctl daemon-reload
chmod +x /etc/systemd/system/ssh_remote_access.service
systemctl enable --now ssh_remote_access.service
