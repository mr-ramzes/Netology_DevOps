Согласно .gitignore будут исключены:

- \*\*/.terraform/\*
*все файлы внутри директорий .terraform (которые, в свою очередь, могут быть поддиректориями любого уровня)*
***Вопрос: не совсем понял, чем это будет отличаться от .terraform/\*?***

- \*.tfstate
\*.tfstate.\*
*любые файлы с расширением .tfstate или содержащие в своем названии .tfstate.*

- crash.log
crash.*.log
*файлы crash.log или файлы, начинающиеся на crash или оканчивающиеся на .log в любой директории репозитория*

- \*.tfvars
\*.tfvars.json
*любые файлы с расширением .tfvars или оканчивающиеся на .tfvars.json*

- override.tf
override.tf.json
\*_override.tf
\*_override.tf.json
*файлы override.tf, override.tf.json или оканчивающиеся на _override.tf и _override.tf.json в любой директории репозитория*

- .terraformrc
terraform.rc
*файлы .terraformrc и terraform.rc в любой директории репозитория*

one_more_line