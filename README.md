<img src="https://www.ehacking.net/wp-content/uploads/2014/02/bwapp.jpg"
     alt="bWAPP"
     style="float: left; margin-right: 10px;" />

# bWAPP-Docker

As the title suggests, this is a simple Docker image for the OWASP bWAPP application designed to teach and demonstrate various web app vulnerabilities.

# Why?

Installing and configuring PHP based web apps can be quite time consuming as you need to install various packages like PHP, Apache, MySQL etc...
This Docker image eliminates(automates;)) this tedious process and provides you with a click and run solution that will provide you with a bWAPP instance in a few seconds.

# Setup

### 1. Clone the repository

```bash
git clone https://github.com/dockfiles/bWAPP-a-buggy-web-application-.git bwapp
```

cd into the new directory

```bash
cd bwapp
```

## Running the bWAPP container

```
docker compose up -d
```

## Installing bWAPP

- After running the bWAPP container, navigate to http://localhost/install.php to complete the bWAPP setup process.
