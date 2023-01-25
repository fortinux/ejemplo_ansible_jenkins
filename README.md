# Ejemplo Integración de Ansible con Jenkins
## ejemplo_ansible_jenkins
  
- En este ejemplo el servidor Jenkins leerá el fichero *Jenkinsfile* del repositorio para ejecutar la *pipeline*.
- Pasos:
- En Jenkins se crea una nueva *pipeline* donde se selecciona *Pipeline script from SCM*, se agrega la dirección de este repositorio y se modifica a *main* la opción *Branch specified*.
- Finalmente se ejecuta la tarea. 
