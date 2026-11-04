# Lab: OverTheWire Bandit (Niveles 0-10)

**Semana:** 1
**Fecha inicio:** 2026-11-04
**Plataforma:** OverTheWire (bandit.labs.overthewire.org)

## Objetivo

Practicar comandos fundamentales de Linux: navegación, lectura de archivos, búsqueda, permisos, pipes, SSH.

## Scope

- Target: `bandit.labs.overthewire.org` puerto 2220
- Herramientas: SSH, comandos básicos de Linux (`ls`, `cat`, `find`, `grep`, `file`, `du`, `sort`, `uniq`, `strings`, `base64`, `tr`)
- Limitaciones: solo interacción con el servidor de OverTheWire (entorno controlado)

## Conexión

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
# Password nivel 0: bandit0
```

## Progreso

| Nivel | Comando clave | Concepto aprendido | Completado |
|-------|--------------|-------------------|------------|
| 0 → 1 | `cat readme` | Leer archivos con cat | |
| 1 → 2 | `cat ./-` | Archivos con nombres especiales | |
| 2 → 3 | `cat "spaces in filename"` | Escapar espacios | |
| 3 → 4 | `ls -la`, `cat .hidden` | Archivos ocultos (dot files) | |
| 4 → 5 | `file ./*`, `cat` | Identificar tipos de archivo | |
| 5 → 6 | `find -size 1033c ! -executable` | Búsqueda por tamaño y permisos | |
| 6 → 7 | `find / -user bandit7 -group bandit6 -size 33c` | Búsqueda por owner/group | |
| 7 → 8 | `grep millionth data.txt` | Búsqueda de texto con grep | |
| 8 → 9 | `sort data.txt \| uniq -u` | Pipes, sort, uniq | |
| 9 → 10 | `strings data.txt \| grep "=="` | Extraer strings de binarios | |

## Notas

- Las passwords cambian periódicamente. No guardar passwords en el repo.
- Cada nivel enseña un concepto de Linux que se usa en pentesting real.
- `cat` para leer, `find` para buscar, `grep` para filtrar, pipes (`|`) para encadenar.

## Aprendizaje

(Completar después de terminar los niveles)

- Qué aprendí:
- Qué me costó:
- Qué investigar más:
