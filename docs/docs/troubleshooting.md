# Solución de problemas

## Error

```text
ollama no se reconoce
```

### Solución

```powershell
ollama --version
```

---

## Error

```text
docker no se reconoce
```

### Solución

Reiniciar Windows.

Verificar:

```powershell
docker --version
```

---

## Error

```text
failed to connect to dockerDesktopLinuxEngine
```

### Solución

Abrir Docker Desktop.

Esperar:

```text
Engine running
```

---

## Error

```text
unexpected EOF
```

### Solución

```powershell
docker pull ghcr.io/open-webui/open-webui:main
```
