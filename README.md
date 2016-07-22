# adminer-sqlite

Adminer login form modification to support SQLite databases. 

Example:

![alt tag](https://raw.githubusercontent.com/orlov0562/adminer-sqlite/master/example.png)

#Usage

1. Put files to ``www/example.com/adminer/`` folder
2. Put db or symlink to db into ``www/adminer/sqlite`` folder
3. Open ``example.com/adminer`` and select SQLite driver
4. At this point you should see databases in Database dropdown list. 
5. Select database and press [Login] button

#Configuration

You can find settings in the top of ``adminer-sqlite-login.php`` file

Keep in mind that default setting intended for local servers and shouldn't be used for web without additional protection.

``SQLiteShowDBList`` = Allow to show/hide dropbox with database list. Values: true | false

``SQLiteCredentials`` = Allow to set credentials or skip credentials verification. Values: null | 'username:password'

``SQLiteDir`` = folder name that contains sqlite databases
