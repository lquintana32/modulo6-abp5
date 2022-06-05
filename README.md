Map del sitio:

Navbar tiene los accesos a las distintas urls de la aplicacion

Home -- http://127.0.0.1:8000
Es un landing page que permite navegar

Crear Usuario -- http://127.0.0.1:8000/crearusuario
Formulario para crear User propios de Django

Login Usuario -- http://127.0.0.1:8000/loginu
Login que permite loguear User creados en el formulario anteriro o directamente por el administrador de Django

Crear Cliente -- http://127.0.0.1:8000/cliente2
Crea cliente que corresponde a un modelo de prueba creado para testear vistas, etc.

Ver Cliente -- http://127.0.0.1:8000/clientes/
Muestra los clientes anteriores en pantalla, tambien a modo de prueba


ABP5:

Para la revision de la actividad se sugiere crear un User a traves de la ventana de administracion propia de Django o a traves de la url /crearusuario (disponible en el Navbar) y luego verificarlo en la url /login (tambien disponible en el Navbar). Si el login es correcto envia a un template de bienvenida en el que muestra el mensaje "Bienvenido {{User}}, login exitoso!!!"
