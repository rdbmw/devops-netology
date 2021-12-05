# devops-netology
файл terraform/.gitignore содержит правила для игнорирования:
- всех директории .terraform любого уровня вложенности в директорию terraform;
- файлы *.tfstate, *.tfstate.* и *.tfvars любого уровня вложенности в директорию terraform
- файлы crash.log, override.tf, override.tf.json, .terraformrc, terraform.rc директории terraform;
- файлы, содержащие в названии паттерны _override.tf и _override.tf.jsoncrash.log любого уровня вложенности в директорию terraform;
new-line
