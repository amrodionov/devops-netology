#  Игнорирование содержимого директорий terraform любой вложенности
**/.terraform/* - игнорировать каталог

# файлы с расширением tfstate и все архивные версии.
*.tfstate
*.tfstate.* 

# Файлы с именем crash.log
crash.log 

##игнорирование конфигураций коммандной строки тераформ?!!
.terraformrc
terraform.rc
