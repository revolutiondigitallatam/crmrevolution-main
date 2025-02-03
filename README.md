# CRMREVOLUTION
Sistema de autoservicio
========================================
DIAGRAMA DE INSTALACIÓN DEL WHATICKET
========================================

SISTEMA OPERATIVO UBUNTU 24.04

-------------------------------

1. Contrate un VPS:

 - Empecé con el plan KVM2. Después de un tiempo, ante el aumento de la demanda, cambié a KVM4.

 - ¡Empieza despacio!

2. Compra un dominio:

3. Crea 2 subdominios para whaticket

4. Descargue la fuente de Whaticket:

5. Sube el código fuente a tu github.

6. Instalar whaticket

6.1 Acceso remoto vía ssh

6.2 Crear una cuenta para el usuario de implementación

6.3 Agregar el usuario de implementación al grupo sudo

6.4 Acceder al VPS con el usuario de implementación


COMANDO DE INSTALACIÓN DE CRMREVOLUTION

sudo apt install -y git && git clone https://github.com/weliton2k/instalador-whaticket-main-v.10.0.1.git && sudo chmod -R 777 instalador-whaticket-main-v.10.0.1 && cd instalador-whaticket-main-v.10.0.1 && sudo ./install_primaria


https://github.com/usuario/whaticket.git


