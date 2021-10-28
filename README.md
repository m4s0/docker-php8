# Application
Application runs with PHP 8

#### Docker

```
cd docker
```

Build container
```
docker-compose build
```

Run container
```
docker-compose up -d
```

Enter into php container
```
docker-compose run php bash
```

#### Init Application

install dependencies
```
make install
``` 

#### Tests

Application has been designed using a Test Driven Design approach and PHPUnit

run tests
```
make test
``` 

#### Coding Standards

```
make cs
``` 

#### Static Code Analysis

```
make stan
``` 
