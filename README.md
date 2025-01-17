# GLPI Quick Start

## Install glpi with Docker Compose

### Prerequisites

**Install Docker and Docker Compose**
- [Debian](https://docs.docker.com/engine/install/debian/)
- [Ubuntu](https://docs.docker.com/engine/install/ubuntu/)
- [CentOS](https://docs.docker.com/engine/install/centos/)
- [RHEL](https://docs.docker.com/engine/install/rhel/)

### 1. Set variables about DB in docker-compose.yml file
```
MYSQL_ROOT_PASSWORD: "<YOUR_MYSQL_ROOT_PASSWORD>"
MYSQL_DATABASE: "glpi"
MYSQL_USER: "glpi"
MYSQL_PASSWORD: "<YOUR_MYSQL_PASSWORD>"
```

### 2. Execute docker compose file
```bash
docker compose up -d
```

### 3. Connect your glpi server
![setup0](./reference_images/setup_0.png)

![setup1](./reference_images/setup_1.png)

![setup2](./reference_images/setup_2.png)

![setup3_1](./reference_images/setup_3_1.png)

![setup3_2](./reference_images/setup_3_2.png)

![setup4](./reference_images/setup_4.png)

![setup5](./reference_images/setup_5.png)

![setup6](./reference_images/setup_6.png)

![setup7](./reference_images/setup_7.png)

![setup8](./reference_images/setup_8.png)

![setup9](./reference_images/setup_9.png)

![setup10](./reference_images/setup_10.png)

![setup11](./reference_images/setup_11.png)

![setup12](./reference_images/setup_12.png)

![setup13](./reference_images/setup_13.png)