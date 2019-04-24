1. Installez Ansible sur votre machine  /   https://bit.ly/2KHuyY5

2. Clonez le projet

3. Dans le dossier host_vars, changez les ip dans vm_1.yml et vm_2.yml par les ip de vos machines distantes. 
Si vous voulez ajoutez d'autres machines, créer un nouveau fichier pour chaque nouvelle ip et mettez le nom du fichier sous le rôle souhaité dans hosts.ini

4. Lancez la commande 'ansible-playbook ./plays/playbook.yml' dans votre terminal
