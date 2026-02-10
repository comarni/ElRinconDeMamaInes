# El Rincón De Mamá Inés - Pastelería con Stripe

Sistema de pedidos online con integración de pagos Stripe para la pastelería artesanal "El Rincón De Mamá Inés".

## 🚀 Quick Start (Desarrollo Local)

### Requisitos
- Node.js 16+
- npm o yarn
- Claves de Stripe (test o live)

### Instalación

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/comarni/ElRinconDeMamaInes.git
   cd ElRinconDeMamaInes
   ```

2. **Configurar variables de entorno**
   ```bash
   cd server
   cp .env.example .env
   ```
   Edita `.env` con tus claves de Stripe

3. **Instalar dependencias**
   ```bash
   npm install
   ```

4. **Iniciar servidor**
   ```bash
   npm start
   ```

5. **Acceder a la plataforma**
   - Local: `http://localhost:3001`

## 🌐 Despliegue en Hostinger

Ver [GUÍA DE DESPLIEGUE](./DEPLOYMENT.md) para instrucciones completas.

### Resumen rápido:
1. Conectar repositorio GitHub en Hostinger
2. Configurar Node.js 16+
3. Añadir variables de entorno (claves LIVE de Stripe)
4. Configurar webhooks en Stripe Dashboard
5. Verificar despliegue

## 🛡️ Seguridad

⚠️ **IMPORTANTE:**
- Nunca subas `.env` a GitHub (ya está en `.gitignore`)
- Las claves secretas de Stripe deben estar en variables de entorno
- Usa claves LIVE solo en producción
- Cambia las claves si accidentalmente fueron expuestas

## 📞 Contacto

- WhatsApp: +34 661 09 97 82
- Email: 01elrincondemamaines@gmail.com
- Instagram: @el_rincon_de_mama_ines

---

**Última actualización:** Febrero 2026
Pastelería, Reposteria Alcobendas
