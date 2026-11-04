# Ethical Hacking & Penetration Testing — Portfolio

Repositorio de aprendizaje y práctica de ciberseguridad.
Basado en el curso *Ethical Hacking & Penetration Testing Master Guide 2026*.

> **Uso responsable:** todo ejercicio práctico se realiza exclusivamente en sistemas propios,
> laboratorios deliberadamente vulnerables o plataformas que autoricen expresamente las pruebas.

## Estructura

```
labs/
  semana-NN-tema/
    lab-nombre/
      README.md        ← objetivo, scope, herramientas, pasos
      evidence/        ← screenshots relevantes
      scripts/         ← scripts propios del lab
      notes.md         ← apuntes y aprendizajes
      remediation.md   ← mitigación/defensa
scripts/               ← scripts reutilizables
tools/                 ← configs de herramientas
cheatsheets/           ← referencia rápida
```

## Plan de estudio (12 semanas)

| Semana | Tema | Práctica |
|--------|------|----------|
| 1 | Linux básico y terminal | OverTheWire Bandit 0-10 + Linux Survival |
| 2 | Redes I | Packet Tracer + Wireshark en LAN |
| 3 | Redes II / TCP | Wireshark + Nmap contra scanme y VMs |
| 4 | HTTP y web | PortSwigger Web Security Academy |
| 5 | Linux administración | VM Ubuntu/Kali + hardening básico |
| 6 | Windows básico | Windows VM + Sysinternals |
| 7 | Git + Python | Repo de notas + scanner de lab |
| 8 | Docker y laboratorio web | OWASP Juice Shop local |
| 9 | Metodología | Mini assessment en Juice Shop |
| 10 | Enumeración | Metasploitable 2 o VulnHub aislada |
| 11 | Reporting | Informe de 3 hallazgos del lab |
| 12 | Consolidación | CTF inicial + walkthrough + publicar notas |

## Rutina de sesión (90 min)

- 10 min → repaso sin apuntes
- 20 min → teoría/documentación
- 45 min → laboratorio
- 10 min → escribir lo aprendido
- 5 min → crear 2 preguntas para próximo repaso

## Revisión espaciada

- **Día siguiente** — intentar explicar sin notas
- **Semana siguiente** — resolver, después consultar nota
- **Mes siguiente** — revisar conceptos clave

## Proyectos de portfolio

1. **Nmap + Wireshark Network Recon Lab** — reconocimiento de red documentado
2. **OWASP Juice Shop Assessment Report** — assessment completo con hallazgos
3. **Windows/AD Home Lab Security Review** — revisión de seguridad de lab Windows

## Buenas prácticas

- No publicar credenciales reales, tokens, cookies ni datos de terceros
- Anonimizar IPs y nombres si el lab no es público
- Explicar objetivo, metodología y aprendizaje
- Incluir mitigación, no solo "cómo explotar"
- Screenshots solo cuando aporten evidencia
- Versionar scripts propios y explicar límites
