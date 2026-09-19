---
name: Historia de usuario
about: Plantilla para cargar una HU con specs, checklist y orden de trabajo
title: "[HU] "
labels: ''
---

## Historia
Como [rol], quiero [acción], para [beneficio].

**Épica / Milestone:**
**Prioridad:** 🔴 Must have / 🟠 Should have / 🟡 Could have

## Especificaciones
-

## Backend
- [ ]

## Frontend
- [ ]

## Orden de trabajo
1. Backend crea la estructura base y mergea primero a `testing`
2. Frontend hace `git pull` antes de empezar
3. Backend completa la lógica en su rama
4. Frontend completa la vista en su rama
5. Checkpoint y merge cada 2-3 horas (avisar antes de mergear)
6. Prueba conjunta antes de cerrar el issue

## Ramas
- Backend: `feature/<epica>-<hu>-back`
- Frontend: `feature/<epica>-<hu>-front`
