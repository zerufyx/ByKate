# By Kate · La Silla Roja — concepto

Sitio con reservas en línea y panel para la dueña. **Concepto** de Zerufy Studio.
**En línea:** https://zerufyx.github.io/ByKate/

| Archivo | Qué es |
|---|---|
| `index.html` | Sitio: servicios, horarios libres y reserva de citas |
| `admin.html` | Panel: citas, servicios, horario, días bloqueados y reseñas |

**Supabase:** sistema de Reservas, tablas `bk_*` (`bk_services`, `bk_hours`, `bk_blocks`, `bk_appointments`, `bk_reviews`, `bk_settings`, `bk_admins`). Las citas se crean con `bk_book` y los horarios libres salen de `bk_slots`. Solo se usa la llave pública.

---
Hecho por **Zerufy Studio** · zerufystudio.com · El mapa de todos los repos está en el README de `Zerufy-Studio-`.
