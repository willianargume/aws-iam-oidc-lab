# AWS IAM & OIDC Integration Lab

Laboratorio práctico de seguridad en la nube enfocado en la integración de flujos de trabajo (GitHub Actions) con Amazon Web Services (AWS) mediante la federación de identidades con OpenID Connect (OIDC). Esta arquitectura elimina el uso de credenciales estáticas de largo plazo, aplicando el principio de menor privilegio.

## 📁 Contenido del repositorio

🔗 **[Workflow OIDC - GitHub Actions](.github/workflows/aws-oidc.yml)**
Flujo de trabajo automatizado configurado para que GitHub asuma un rol temporal de AWS de manera segura y sin almacenar Access Keys, validando la identidad asumida mediante AWS CLI.

## 🧩 Stack técnico

* **Amazon Web Services (AWS):** IAM Roles, Identity Providers (OIDC), Trust Policies.
* **GitHub:** GitHub Actions, Tokens OIDC.
* **Herramientas:** AWS CLI.

## 🎯 Contexto

Este proyecto expande mi experiencia en la gestión de identidades (IAM) hacia entornos multi-nube (Multi-Cloud). Complementa mis prácticas de gobierno de accesos aplicando modelos de autenticación modernos y efímeros (Zero Trust) en ecosistemas DevSecOps, asegurando integraciones de infraestructura como código.

## 📫 Contacto

[LinkedIn](https://www.linkedin.com/in/willianargume) · [willian.argume@gmail.com](mailto:willian.argume@gmail.com)
