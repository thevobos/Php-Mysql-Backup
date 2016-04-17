# Php-Mysql-Backup
Php Mysql Backup

    include("dbbackup.php");
  
		$DB = new dbbackup;

		$var = $DB
		  ->username("Mysql Username")
			->password("password")
			->host("localhost / domain / ip")
			->dbname("Db Name")
			->file("Save .sql Path xx/xx/")
			->title("Sql Save Dile name xx.sql")
			->run();
			
