# comandos
Alguns comandos úteis


1. subir um backup de banco mysql numa vps 
  ``` mysql -u root -p < D:/arquivo.sql ```
2. criar um link simbólico para arquivo no linux
  ```ln -s /path/to/file /path/to/symlink ```
3. importar csv no mysql
  ``` mysqlimport --ignore-lines=1  --fields-terminated-by=; --debug --delete --default-character-set="utf8" --local -u root -p Database tablename.csv ```
