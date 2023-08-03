Github has a limitation to upload only files < 25mb. Hence the the below workaround.

1. Unzip mysql-connector-python_1.zip in local machine (call it folder1)
2. Unzip mysql-connector-python_2.zip in location machine (call it folder2). It should contain below 2 files
   _mysql_connector.cpython-38-x86_64-linux-gnu.so
   _mysqlxpb.cpython-38-x86_64-linux-gnu.so
3. Copy the 2 files from folder2 and paste the files under folder1 , "\python\lib\python3.9\site-packages"
4. go back to Folder1 and zip the folder to create a zip file.
5. This zip file created in step 4 needs to be uploaded into lambda function layers for mySQL connectivity.