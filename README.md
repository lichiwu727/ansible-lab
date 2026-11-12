# Laboratorio de Automatización: Ansible + Docker

## Objetivo de la práctica
El objetivo de este laboratorio es desplegar un entorno de pruebas localizado utilizando contenedores Docker que simulan servidores independientes, para luego automatizar tareas de administración de sistemas, aprovisionamiento de archivos y creación de estructuras de directorios utilizando Ansible mediante conexiones nativas de Docker.

## Prerrequisitos
* Docker y Docker Compose instalados.
* Ansible instalado en la máquina host.

## Instrucciones de Despliegue

### 1. Iniciar los contenedores
Desde la raíz del proyecto (`ansible-lab/`), ejecuta el siguiente comando para levantar los servidores en segundo plano:
```bash
docker compose up -d