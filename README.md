# Laboratorio: Integración de AWS IAM con GitHub Actions (OIDC)

Este repositorio contiene la prueba de concepto para conectar GitHub Actions con Amazon Web Services (AWS) utilizando OpenID Connect (OIDC). 

Esta arquitectura de identidad web elimina la necesidad de almacenar credenciales estáticas de largo plazo (Access Keys) dentro de los secretos de GitHub, mejorando la seguridad y reduciendo el riesgo de exposición.

**Recursos implementados:**
- AWS IAM: Identity Provider (GitHub), Rol IAM, Políticas de Confianza (Trust Policies).
- GitHub Actions: Flujo de trabajo para asumir el rol de AWS y ejecutar comandos mediante AWS CLI.
