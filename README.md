## Database 
CREATE DATABASE attendance;
use attendance;
### Department Table
CREATE TABLE department(
D_id INT PRIMARY KEY AUTO_INCREMENT,
d_name VARCHAR(255) NOT NULL,
role VARCHAR(255) NOT NULL
);
