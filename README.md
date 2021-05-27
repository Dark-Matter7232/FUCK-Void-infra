# FUCK-Void-Package-build-infra
FUCK-void is a custom xbps-src repo / custom repo(with xbps binaries) that includes restricted packages.

## Adding the custom repo 
```
sudo sh -c 'echo "repository=https://Dark-Matter7232.gitlab.io/FUCK-Void/generic/" >> /etc/xbps.d/10-FUCK-Void.conf'
sudo xbps-install -Su
sudo xbps-install -S packagename
```
