# Laboratorio-2

El presente documento describe una plantilla de AWS CloudFormation diseñada para desplegar una arquitectura de alta disponibilidad (HA) que consta de 5 servidores EC2 ejecutando el servidor web NGINX, distribuidos en 2 Zonas de Disponibilidad (AZs) y balanceados mediante un Application Load Balancer (ALB).

La solución garantiza que, ante la caída de uno o varios servidores, el tráfico sea redirigido automáticamente a las instancias saludables, minimizando el tiempo de inactividad.
