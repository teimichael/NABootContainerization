# NABootContainerization
A container-based deployment for NA Boot Plan. \
NA Boot Plan is a full-stack web development framework that aims to provide swift construction for web applications. \
This project provides a scaffold to build web applications on NA Boot Plan with containerization support.

## Main Components
- [x] [**Authentication System**](https://github.com/teimichael/NABootAuth)
- [x] [**Backend System**](https://github.com/teimichael/NABootWeb)
- [x] [**Frontend System**](https://github.com/teimichael/NABootApp)
- [x] [**WebSocket System**](https://github.com/teimichael/NABootSocket)
- [x] **SQL Databases**
- [x] **Static Resource Server**
- [x] **Containerization**

## Main Features
- [x] High cohesion, low coupling
- [x] Classic service-oriented architecture
- [x] Lightweight
- [x] Containerized
- [x] Easy-to-use
- [x] WebSocket support

## Architecture

![Architecture](./document/Architecture.png)

## Usage
### Pull projects from GitHub
```bash
chmod u+x ./cloneRepositories.sh
./cloneRepositories.sh
```

### Create static folder
```bash
chmod u+x ./createStaticFolder.sh
./createStaticFolder.sh
```

### Start up projects
```bash
docker-compose up
```

#### Deamon mod
```bash
docker-compose up -d
```

### Shut down projects
```bash
docker-compose down
```

#### Shut down and clear projects
```bash
docker-compose down --rmi 'all'
```

## Application
### Boostim
Boostim is a set of solutions for instant messaging. \
For more information, please refer to [Boostim](https://github.com/teimichael/BoostimQuickStart).

### Clouder
A private cloud web service for static resource storage on clouds supported by GCP storage. \
Related resources:
- [Clouder Web](https://github.com/teimichael/ClouderWeb)
- [Clouder Auth](https://github.com/teimichael/ClouderAuth)
- [Clouder App](https://github.com/teimichael/ClouderApp)
- [Clouder Web Client](https://github.com/teimichael/ClouderWebClient)


## Related Projects
- [NA Boot Auth](https://github.com/teimichael/NABootAuth)
- [NA Boot Web](https://github.com/teimichael/NABootWeb)
- [NA Boot App](https://github.com/teimichael/NABootApp)
- [NA Boot Socket](https://github.com/teimichael/NABootSocket)