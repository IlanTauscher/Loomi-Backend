# Loomi-Backend
Proyecto de ejemplo que se conecta a Supabase desde Node.js.

## Configuración

1. Copie el archivo `.env.example` a `.env` y complete `SUPABASE_URL`, `SUPABASE_KEY` y `DATABASE_URL` con los datos de su proyecto en Supabase.
2. Instale las dependencias con `npm install`.
3. Ejecute `node index.js` para iniciar la aplicación.

La inicialización del cliente se realiza con la biblioteca [`@supabase/supabase-js`](https://supabase.com/docs/reference/javascript/start). Consulte la [documentación oficial](https://supabase.com/docs) para más detalles sobre cómo trabajar con la API de Supabase y conexiones a PostgreSQL.
