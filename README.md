# gerelmaa
Ашиглах заавар:

1.Download хийнэ: gerelmaa'Folder name '

2.file-> Open Folder in Visual Studio
    Visual download npm install in terminal:

3.MySql open Database: User table name accounts

 CREATE TABLE IF NOT EXISTS `accounts` (
`id` int(11) NOT NULL,
`username` varchar(50) NOT NULL,
`password` varchar(255) NOT NULL,
`email` varchar(255) NOT NULL,
`profilePicture` varchar(255)
) ENGINE=InnoDB AUTO_INCREMENT=2 DEFAULT CHARSET=utf8;

ALTER TABLE accounts ADD PRIMARY KEY (id); ALTER TABLE accounts MODIFY id int(11) NOT NULL AUTO_INCREMENT,AUTO_INCREMENT=2;

4.MySql open Database: Blog table name blogPost

CREATE DATABASE IF NOT EXISTS nodelogin DEFAULT CHARACTER SET utf8 COLLATE utf8_general_ci; USE nodelogin;

CREATE TABLE IF NOT EXISTS blogPost ( id int(11) NOT NULL, title varchar(50) NOT NULL, desTitle varchar(50) NOT NULL, description varchar(255) NOT NULL, blogPhoto varchar(255) NOT NULL, date varchar(255), user varchar(255) NOT NULL, category varchar(50) ) ENGINE=InnoDB AUTO_INCREMENT=2 DEFAULT CHARSET=utf8;

ALTER TABLE blogPost ADD PRIMARY KEY (id); ALTER TABLE blogPost MODIFY id int(11) NOT NULL AUTO_INCREMENT,AUTO_INCREMENT=2;

5.Create file: .env

DB_HOST = 'localhost' DB_USERNAME = 'root' DB_PASSWORD = '99091557' DB_NAME = 'nodelogin'

SERVER_PORT = 3000
Open Terminal Start : npm start

6.Open browser: write

localhost:3000

<img src="https://scontent.fuln1-1.fna.fbcdn.net/v/t1.15752-9/175831263_4152958848088628_8430165897767099346_n.png?_nc_cat=111&ccb=1-3&_nc_sid=ae9488&_nc_ohc=UHi-udW04ToAX_5N83X&_nc_ht=scontent.fuln1-1.fna&oh=72a09aeafaba7734f961de7c83d4abdf&oe=60A2D5EF" />
