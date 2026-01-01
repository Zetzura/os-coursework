# Week 5 – Advanced Security and Monitoring

## Fail2Ban
```
sudo apt install fail2ban -y
sudo systemctl enable fail2ban
sudo systemctl start fail2ban
```

## Automatic Updates
```
sudo apt install unattended-upgrades
sudo dpkg-reconfigure unattended-upgrades
```

These measures protect the system from brute-force attacks and unpatched vulnerabilities.
