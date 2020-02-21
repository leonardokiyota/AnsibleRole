Role lpi2-Exam201
=========

Esta role instala alguns pacotes no SO Linux para o Exame LPIC-2-201, foi testado em sistema Opensuse 15.1 Leap,
Debian 10, CentOS 8, Ubuntu 18.04 e Ubuntu 19.04.
A lista de pacotes estão no arquivo "main.yml" dentro do diretório "defaults".
Essa role adiciona o repositório epel-release em sistema baseado em Red Hat.
Sinta-se livre para adicionar mais pacotes importantes para o Exame 201.

This role install some packages in your Linux OS for the Exam LPIC-2-201, it was tested in system like Opensuse 15.1 Leap,
Debian 10, CentOS 8, Ubuntu 18.04 and Ubuntu 19.04.
The list of packages are in the file "main.yml" inside of directory "defaults".
This role add epel-release repository in system based in Red Hat.
Feel free to add some important packages for the Exam 201.

Exemplo Playbook / Example Playbook
----------------

    - hosts: Linux-LPIC2-201
      roles:
         - lpi2-Exam201

License
-------

BSD

Informações do Autor / Author Information
------------------

Leonardo Kiyota - Email: leokiyota@gmail.com
