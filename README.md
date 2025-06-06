## Database Creation
CREATE DATABASE attendance;<br>
use attendance;<br>
### Department Table
CREATE TABLE department(<br>
D_id INT PRIMARY KEY AUTO_INCREMENT,<br>
d_name VARCHAR(255) NOT NULL,<br>
role VARCHAR(255) NOT NULL<br>
);<br>
### Slot Table
CREATE TABLE slot(<br>
sl_id INT primary key auto_increment,<br>
start TIME NOT NULL,<br>
end TIME NOT NULL,<br>
slot_name VARCHAR(50) UNIQUE NOT NULL<br>
);<br>

