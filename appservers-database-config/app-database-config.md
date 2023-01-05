## Create a Database config file in the application servers 
vi dbinfo.inc

## Copy and Past the Below Data in the file after updating
```bash
<?php

define('DB_SERVER', 'database-1.c3z0itrznerp.af-south-1.rds.amazonaws.com');
define('DB_USERNAME', 'phpappadmin');
define('DB_PASSWORD', 'phpappadmin');
define('DB_DATABASE', 'phpappdatabase');

?>
```
