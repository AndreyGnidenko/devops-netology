Будут игнорироваться следующие файлы (относится к папке terraform)

1. Все содержимое папок с названием .terraform на любом уровне вложенности
2. Все файлы с расширением tfstate
3. Все файлы, расширение которых начинается с tfstate. 
4. Файл с именем crash.log
5. Все файлы с расширением tfvars
6. Файл с именем override.tf
7. Файл с именем override.tf.json
8. Файлы с расширением tf, имя которых заканчивается на _override
9. Файлы с расширением tf.json, имя которых заканчивается на _override
10. Файл с именем .terraformrc
11. Файл terraform.rc

Changed and committed from IDE