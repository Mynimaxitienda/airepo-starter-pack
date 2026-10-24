# Security Policy - Mynimaxitienda RepoStarterPack

## Objetivo
Estrategia cloud-first multi-plataforma con seguridad por defecto.

## Supported Versions
| Version | Supported |
| ------- | --------- |
| main    | ✅ |
| develop | ✅ |

## Reporting a Vulnerability
1. NO abras Issue público
2. Ve a Security > Report a vulnerability
3. Respuesta < 72h

## Buenas prácticas
- .env en .gitignore, usar .env.example
- Firestore Rules: solo auth
- main protegida: solo PR
- Secrets vía GitHub Secrets
- npm audit

## Checklist
- [ ] Inputs validados
- [ ] Rules actualizadas
- [ ] Env en .env.example
- [ ] npm audit
