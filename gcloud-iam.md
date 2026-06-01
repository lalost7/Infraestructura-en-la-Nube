# Práctica IAM

## Salida del comando
bindings:
- members:
  - user:lalitosantos309@gmail.com
  role: roles/owner
- members:
  - serviceAccount:auditor-plataforms@project-0df7fc15-59d3-496b-95b.iam.gserviceaccount.com
  role: roles/viewer
etag: BwZIKakwNoI=
version: 1
## Conclusión

Utilizar la llave privada de una cuenta administradora dentro del código fuente representa un riesgo grave de seguridad, ya que puede ser expuesta accidentalmente.

Las cuentas de servicio con permisos mínimos permiten reducir riesgos y aplicar correctamente el Principio de Menor Privilegio.
## Fuentes

Google Cloud. (2026). GCP Identity and Access Management (IAM) overview: Understanding roles and service accounts.

https://docs.cloud.google.com/iam/docs/overview?hl=es-419

Google Cloud. (2026). Google Cloud CLI reference: gcloud iam service-accounts syntax.

https://cloud.google.com/sdk/gcloud/reference/iam/service-accounts
