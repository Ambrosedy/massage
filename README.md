# Massage

+ 将email jar包导入maven项目：
    1. 手动安装jar包到maven仓库：
    ```
  mvn install:install-file -Dfile=<path-to-file>
  or
  mvn install:install-file -Dfile=<path-to-file> -DgroupId=<group-id> -DartifactId=<artifact-id> -Dversion=<version>
  
  example:
  mvn install:install-file –Dfile=C:\dev\app.jar -DgroupId=com.roufid.tutorials -DartifactId=example-app -Dversion=1.0
  
  ```
  
  + IDEA 切换WSL ： "cmd.exe" /k "wsl.exe"
