# Fx Self Monitor from  Uptime Kuma

This is a self -hosted monitoring tool forked from
<a href= https://github.com/louislam/uptime-kuma> Uptime Kuma</a>

Check the above link for Features and updates

## Prerequisite

**Docker** needs to be installed on your system. If it's not installed, 
If you are interested in downloading docker refer the above repo and follow those steps for local testing

If you are ready install Docker
refer below steps

### Docker Installation in Linux

1. Install Docker in Linux
```bash
sudo apt install docker.io -y
```
2. Install Docker Compose
```bash
sudo apt install docker-compose -y
```

## Testing Locally

In Terminal type below command
```bash
sudo docker-compose up -d
```
To check the status in terminal, use below command
```bash
sudo docker ps
```
Navigate to ip address of the container with Port: 3001
By default Link: 0.0.0.0:3001

### To Bring it down

Use the below command to bring it down
```bash
sudo docker-compose down
```
