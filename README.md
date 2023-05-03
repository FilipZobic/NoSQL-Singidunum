## About
___

* Course name: **NoSQL databases**

* Course professor: **Prof. Doc. Branko Perisic**

## Requirements

___

* Docker is installed see [Installing docker](https://docs.docker.com/engine/install/).

## Local instances.

___

### Lunch instance:

`docker-compose -f REPLACE_WITH_FILE_NAME up`

### Shutdown instance:

`docker-compose -f REPLACE_WITH_FILE_NAME down`

### Connecting to instance.

| IP              | Username | Password | GUI IP          |
|-----------------|----------|----------|-----------------|
| localhost:XXXXX | root     | root     | localhost:XXXXX |

Password & username will be the same for all instances.

Some `docker-compose` files will lunch a GUI instance look into the file to see if its available & credentials.

Otherwise you can use your client of choice for example:
* DataGrip supports (multiple databases)
* intellij ultimate (multiple databases)
* MySQL Workbench (MySQL, MariaDB)
* MongoDB Compass (MongoDB)

`TODO for admin: These GUIS should be optional enable docker-compose profiling`

# Remote instances

___

Plan is to have shared instance with auditing
enabled some users will have read/write/administration
rights others just write can connect from anywhere.

With auditing all changes made during exercise section of the course will be recorded.

| Database | Online                                   | IP  | Auditing enabled                         | Hosting solution                                        |
|----------|------------------------------------------|-----|------------------------------------------|---------------------------------------------------------|
| MongoDB  | <span style="color:red">**False**</span> | N/A | <span style="color:red">**False**</span> | [Atlas MongoDB](https://www.mongodb.com/atlas/database) |
| MySQL    | <span style="color:red">**False**</span> | N/A | <span style="color:red">**False**</span> | N/A                                                     |

* *username*: request from administrator

* *password*: request from administrator

___