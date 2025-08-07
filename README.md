# n8nfly.template

Despliegue de n8n en Fly.io con configuración optimizada:

- Región primaria: Guadalajara (`gdl`)
- 2 máquinas, solo 1 activa
- Volumen persistente de 1 GB
- Autenticación básica (`admin` / `tusecreto`)

---

## 🚀 Comandos esenciales

### Crear volumen persistente (una vez):
```bash
fly volumes create datos_n8n --region gdl --size 1
