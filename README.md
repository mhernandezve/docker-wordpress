# docker-wordpress
Setup for WordPress and MySQL on docker-compose 

#### Use: 

`# git clone https://github.com/mhernandezve/docker-wordpress.git`

`# cd docker-wordpress`

`# docker-compose up`

MySQL persistence added in line:

`    volumes:`
`      - "./mysql-data/db:/var/lib/mysql"`
