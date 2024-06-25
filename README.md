# devops-netology
New text

Будут игнорироваться файлы внутри директории terraform:

все файлв внутри папки .terraform из любой поддиректории проекта - "**/.terraform/*"
файлы с конкретными названиями: crash.log, override.tf, override.tf.json, .terraformrc, terraform.rc
файлы с этими расширениями: .tfvars и .tfstate- *.tfvars, *.tfstate
файлы подходящие по маске:  .tfstate., crash.*.log, *.tfvars.json, *_override.tf, *_override.tf.json  (* любое количнтсво любых символов)

+text
+fix
