# Pre-entrega 7 – EduTrack

## Monitoreo y auditoría en AWS

Esta entrega presenta el diseño de un plan de monitoreo, alertas y auditoría para la arquitectura de EduTrack.

### Contenido

- Plan de monitoreo con Amazon CloudWatch.
- Dashboard de métricas de infraestructura.
- Matriz de alarmas y notificaciones mediante SNS.
- Auditoría de eventos con AWS CloudTrail.
- Control de cumplimiento mediante AWS Config.
- Controles de seguridad: Security Groups y NACL.

### Arquitectura contemplada

- VPC en `us-east-1`.
- Dos zonas de disponibilidad.
- Application Load Balancer.
- Instancias EC2 en subredes privadas.
- Amazon RDS MySQL Multi-AZ.
- Amazon S3 privado con OAC.
- Amazon CloudFront y AWS WAF.
- Amazon Route 53 con registro A (Alias).

**Nota:** Los dashboards, umbrales y configuraciones presentados son propuestas de diseño y no representan recursos desplegados o mediciones reales de AWS.
