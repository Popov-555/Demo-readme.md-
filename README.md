<?xml version="1.0" encoding="utf-8" ?>
<configuration>


	<connectionStrings>
		<add 
			 name="DefaultConnection"
			 connectionString="Server=localhost,63027;Database=UserDatabase;Trusted_Connection=True"
			 providerName="System.Data.SqlClient"/>

		<add
			 name="ConnectionLocalDb"
			 connectionString="Server=(localdb)\mssqllocaldb;Database=UserDatabase;Trusted_Connection=True;"
			 providerName="System.Data.SqlClient"/>


		<add name="ConnectionSQLite"
			 connectionString="Data Source=FabricShop.db"
			 providerName="System.Data.SQLite" />

	</connectionStrings>


</configuration>
