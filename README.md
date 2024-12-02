# Multiple_network Node by @colonyAirdrops

- Hardware Requirements (8GB RAM, MultiCore, 100GB SSD)

## Prerequisite:
- Bind your wallet at [MultipleNetwork](https://www.app.multiple.cc/#/signup?inviteCode=j5NmewLi) to obtain a Unique Account Identification Code.

## Step by Step Guide
1. Download File
```bash
wget https://cdn.app.multiple.cc/client/linux/x64/multipleforlinux.tar
```
2. Extract File
```bash
tar -xvf multipleforlinux.tar
```
```bash
cd multipleforlinux/
```
3. Grant permissions
```bash
chmod +x ./multiple-cli
```
```bash
chmod +x ./multiple-node
```
4. Configure
```bash
nano /etc/profile
```
- Configure the required parameters:
```bash
PATH=$PATH:/root/multipleforlinux/
```
```bash
source /etc/profile
```
5. Grant permissions
- Return to the root directory and grant permissions:
```bash
chmod -R 777 multipleforlinux
```
6. Run Node
```bash
cd multipleforlinux/
``` 
```bash
nohup ./multiple-node > output.log 2>&1 &
```
- Bind the unique account identifier. After registering an account on Multiple Network’s official website, an unique account identification code will be generated for your record. 
- Input the unique account identification code and PIN code in the command:
```bash
multiple-cli bind --bandwidth-download 100 --identifier XXXXXXXX --pin XXXXXX --storage 200 --bandwidth-upload 100
```

---
- Done !! Feel free to ask queries in telegram channel
- Telegram - https://t.me/colonyairdrops
- Youtube - https://www.youtube.com/@ColonyAirdrops
