# devops-netology
New text

Будут игнорироваться файлы внутри директории terraform:

все файлв внутри папки .terraform из любой поддиректории проекта - "**/.terraform/*"
файлы с конкретными названиями: crash.log, override.tf, override.tf.json, .terraformrc, terraform.rc
файлы с этими расширениями: .tfvars и .tfstate- *.tfvars, *.tfstate
файлы подходящие по маске:  .tfstate., crash.*.log, *.tfvars.json, *_override.tf, *_override.tf.json  (* любое количнтсво любых символов)

Все вышенаписаное создавалось в момент создания домашнего задание через Linux, теперь через GitHub буду подродно со скриншотами описывать процесс выполнения.

**Создание репозитория и первого коммита**

На гитхабе создаем репозиторий, и забираем его к себе на ОС чере git clone


![alt text](https://github.com/mezhibo/devops-netology/blob/afdb630dbdec17699a0025b91bc801d0af3f4071/IMG/1.jpg)

Смотрим статус 

![alt text](https://github.com/mezhibo/devops-netology/blob/afdb630dbdec17699a0025b91bc801d0af3f4071/IMG/2.jpg)


Создаем файл readme.md и смотрим статус гита

![alt text](https://github.com/mezhibo/devops-netology/blob/afdb630dbdec17699a0025b91bc801d0af3f4071/IMG/3.jpg)

Через git diff смотрим что  было и что стало 

![alt text](https://github.com/mezhibo/devops-netology/blob/afdb630dbdec17699a0025b91bc801d0af3f4071/IMG/4.jpg)


Теперь наш фаил помечаем через git add, через git diff --staged смотрим что было и что добавилось, и делаем First commit (приложил скриншот уже после выполненых других задания, так как не заскриншотил первый коммит, но его можно будет увидеть на скрине при выводе git log)

![alt text](https://github.com/mezhibo/devops-netology/blob/3f4362d579296826ff96625c26573c190af92893/IMG/12.jpg)



**Создание файлов .gitignore и второго коммита**

Теперь создадним наш второй коммит и настроим гитигнор для папки terraform
 Описание того что прописано в gitignore
"Будут игнорироваться файлы внутри директории terraform:

все файлв внутри папки .terraform из любой поддиректории проекта - "**/.terraform/*"
файлы с конкретными названиями: crash.log, override.tf, override.tf.json, .terraformrc, terraform.rc
файлы с этими расширениями: .tfvars и .tfstate- *.tfvars, *.tfstate
файлы подходящие по маске:  .tfstate., crash.*.log, *.tfvars.json, *_override.tf, *_override.tf.json  (* любое количнтсво любых символов)"

![alt text](https://github.com/mezhibo/devops-netology/blob/3f4362d579296826ff96625c26573c190af92893/IMG/6.jpg)


**Эксперимент с удалением и перемещением файлов (третий и четвёртый коммит)**

Создаем 2 файла, один удаляем, второй переименовываем

![alt text](https://github.com/mezhibo/devops-netology/blob/3f4362d579296826ff96625c26573c190af92893/IMG/8.jpg)


![alt text](https://github.com/mezhibo/devops-netology/blob/3f4362d579296826ff96625c26573c190af92893/IMG/9.jpg)

**Проверка изменения**

Теперь смотрим вывод команды git log и видим тот самый первый коммит, скриншот которого пришлось делать позже)))

![alt text](https://github.com/mezhibo/devops-netology/blob/3f4362d579296826ff96625c26573c190af92893/IMG/10.jpg)


**Отправка изменений в репозиторий**

Ну и теперь отправим все изменения на ГитХаб, делаем git push, ввоодим логин и акцесс токен, и видим успешный пуш в репозиторую на гитхаб.

![alt text](https://github.com/mezhibo/devops-netology/blob/3f4362d579296826ff96625c26573c190af92893/IMG/11.jpg)
