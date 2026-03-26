# Docker-Ansible Automation Lab

Este repositorio contiene un laboratorio de automatización diseñado para gestionar contenedores Docker mediante **Ansible**.

## 🚀 Funcionalidades
* **Gestión de Inventario:** Configuración de nodos mediante archivos `.ini`.
* **Orquestación:** Despliegue y verificación de estados en contenedores Alpine y Nginx.
* **Limpieza Automática:** Playbook con lógica de remoción de archivos temporales para mantener el entorno limpio.

## 🛠️ Requisitos
* Ubuntu 24.04 (WSL2)
* Ansible 2.16+
* Docker Desktop

## 🔧 Ejecución
Para ejecutar este laboratorio, usa el siguiente comando:
```bash
ansible-playbook -i hosts.ini playbook-test.yalm
