# devops-netology
first_line

Локальные директории Terraform:

Все содержимое директорий .terraform/ в любом месте проекта.
Файлы состояния Terraform (.tfstate):

Файлы с расширением .tfstate.
Файлы, начинающиеся с .tfstate..
Файлы с логами сбоев (crash logs):

Файл crash.log.
Файлы, начинающиеся с crash. и заканчивающиеся на .log.
Файлы переменных Terraform (.tfvars), которые могут содержать чувствительные данные:

Файлы с расширением .tfvars.
Файлы с расширением .tfvars.json.
Файлы переопределений Terraform (override files), которые используются для локальных изменений:

Файлы override.tf.
Файлы override.tf.json.
Файлы, заканчивающиеся на _override.tf.
Файлы, заканчивающиеся на _override.tf.json.
Временные файлы блокировки, созданные командой terraform apply:

Файл .terraform.tfstate.lock.info.
Файлы конфигурации CLI Terraform:

Файл .terraformrc.
Файл terraform.rc.
Eсть исключения для override файлов, которые могут быть добавлены в версионный контроль с помощью шаблонов отрицания, например:

!example_override.tf.
