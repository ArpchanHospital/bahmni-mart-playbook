# bahmni-mart-playbook

## For Bahmni-mart installation please do the following:

* Before running the installtion please add the following parameters in setup.yml file

  * ANALYTICS_DB_PASSWORD
  * OPENMRS_DB_PASSWORD
  
  
```foo@bar:~# ansible-playbook -i /etc/bahmni-mart-playbook/inventories/bahmni-mart /etc/bahmni-mart-playbook/all.yml --extra-vars '@/etc/bahmni-mart-playbook/setup.yml'```
