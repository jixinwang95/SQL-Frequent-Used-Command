# SQL-Frequent-Used-Command
## to open a db on terminal (inspect only)

1.      cd 
2.      sqlite3 db_name.db
3.      .table #to check tables 
4.      To see columns within table : command = ‘PRAGMA table_info(tweet);’ hit enter (semicolum)


## to get query via python 
To process data from a python script, you have to do (code line in bold):
1.       Import sqlite3 (library to connect the two)
2.       conn=sqlite3.connect(‘path/to/database/db_name.db’)
3.       define a cursor (don’t worry about it, it’s just an object to make queries) : c= conn.cursor()
4.       result=c.execute(‘SELECT user_id FROM user_profile’).fetchall()
          #Make queries : say you want to query the user_id field in the user_profile table : 
          
## sh file command 
1.  i #edit 
2.  :wq #save and quit
3.  :q! #quit 
