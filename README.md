# boltdbweb
A simple web based boltdb GUI Admin panel.


##### Installation
```
go get github.com/daewood/boltdbui
```

##### Usage
```
boltdbui --db-name=<DBfilename>[required] --port=<port>[optional] --static-path=<static-path>[optional]
```
- `--db-name:` The file name of the DB.
    - NOTE: If 'file.db' does not exist. it will be created as a BoltDB file.
- `--port:` Port for listening on... (Default: 8080)
- `--static-path:` If you moved the binary to different folder you can determin the path of the `web` folder. (Default: Same folder where the binary is located.)


##### Example
```
boltdbui --db-name=test.db --port=8080 --static-path=/home/user/github/boltdui
```
Goto: http://localhost:8080

