# Herramientas instaladas — Ethical Hacking Lab

Fecha de instalación: 2026-11-04

## Herramientas de seguridad

| Herramienta | Versión | Uso principal | Semanas |
|-------------|---------|---------------|---------|
| **Nmap** | 7.80 | Escaneo de red, puertos, servicios | 2-3, 10 |
| **Wireshark** (+ TShark) | 4.6.9 | Análisis de tráfico y paquetes | 2-3 |
| **Burp Suite Community** | 2026.3.3 | Proxy HTTP, interceptar/modificar requests | 4, 9 |
| **Docker Desktop** | 29.9.2 | Levantar labs (Juice Shop, Metasploitable) | 8+ |

## Herramientas de desarrollo (preexistentes)

| Herramienta | Versión | Uso |
|-------------|---------|-----|
| **OpenSSH** | 10.3p1 | Conexión a labs remotos (OverTheWire, etc.) |
| **Git** | 2.55.0 | Versionado del portfolio |
| **Python** | 3.14.7 | Scripting, automatización, parseo |
| **PowerShell** | 7.x | Administración Windows, labs semana 6 |

## Rutas de instalación

- Nmap: `C:\Program Files (x86)\Nmap\`
- Wireshark: `C:\Program Files\Wireshark\`
- Burp Suite: `C:\Program Files\BurpSuiteCommunity\`
- Docker: `C:\Program Files\Docker\Docker\`

## Etiquetas de vigencia (del curso)

| Etiqueta | Significado |
|----------|-------------|
| Vigente | Útil hoy y recomendado para práctica |
| Concepto vigente | Herramienta puede estar envejecida, pero idea sigue valiosa |
| Histórico | Solo para contexto, compatibilidad o análisis de legado |
| Laboratorio | Técnica con riesgo, practicar solo en entorno aislado |
| Defensa | Incluye detección, hardening y mitigación |

## Pendientes para instalar más adelante

- **Metasploitable 2** (VM vulnerable) — semana 10
- **OWASP Juice Shop** (Docker) — semana 8: `docker run -p 3000:3000 bkimminich/juice-shop`
- **Sysinternals Suite** — semana 6 (Windows internals)
- **Packet Tracer** (Cisco) — semana 2 (requiere cuenta Cisco NetAcad)
