# aws-iam-security-lab

## 🎥 Video demostración

[![Ver laboratorio en YouTube](images/PortadaIAM.png)](https://www.youtube.com/watch?v=K0wKV3ZbkC8)

Objetivo
Configurar usuarios, roles y políticas de IAM de forma segura siguiendo el principio de mínimo privilegio.
Arquitectura
- Usuario IAM (sin uso de la cuenta root)
- MFA habilitado
- Política personalizada con acceso limitado a S3
Pasos Realizados
- Creación de usuario IAM sin uso de la cuenta root
- Habilitación de MFA
- Adjuntar política personalizada de mínimo privilegio
- Prueba de restricciones de acceso
Mejoras de Seguridad Aplicadas
- Eliminación de permisos de AdministratorAccess
- Aplicación obligatoria de MFA
- Limitación de acceso a S3 únicamente a un bucket específico
Lecciones Aprendidas
- La mala configuración de IAM es la vulnerabilidad número uno en la nube.
