# Assessment

Programing Assessment

  For this project i used WSL with an Ubuntu (master) and Oracle VM VirtualBox also with Ubuntu image (target)

Instructions :

  1. Clone Repo locally
  2. Check ansible-playbook situated at: ~/Assessment/app
  
          - ansible-playbook docker-playbook.yml -i inventory.yaml --check -vvv
   
  3. Run ansible-playbook

          - ansible-playbook docker-playbook.yml -i inventory.yaml
          
  4. RDP into target machine to check container 
  
          - docker ps
  
  
For quick demo i have attached a desktop recording with steps to start ToDo application.
