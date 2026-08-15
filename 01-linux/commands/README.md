# 🧰 Linux Command Reference

A practical command reference for day-to-day administration and DevOps troubleshooting.

## Navigation

### Files & directories
```bash
pwd
ls -lah
cd /path
mkdir -p project/logs
cp source.txt backup.txt
mv old.txt new.txt
rm -rf temp/
```

### Search & text processing
```bash
grep -i "error" app.log
find /var/log -type f -name "*.log"
cat file.txt
less file.txt
sort users.txt
awk '{print $1}' file.txt
sed 's/old/new/g' file.txt
```

### Processes & services
```bash
ps aux
top
systemctl status nginx
systemctl restart nginx
journalctl -u nginx --since "1 hour ago"
```

### Networking
```bash
ip addr
ip route
ss -tulpn
curl -I https://example.com
nslookup example.com
ssh user@server
```

### Storage
```bash
df -h
du -sh /var/log/*
lsblk
mount
```

> Tip: Commands should be learned as part of troubleshooting scenarios, not memorized in isolation.
