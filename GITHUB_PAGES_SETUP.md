# Publicar Politica de Privacidad en GitHub Pages

## 1) Conectar este proyecto a GitHub

Desde la raiz del proyecto:

```powershell
git remote add origin https://github.com/TU_USUARIO/TU_REPO.git
git push -u origin feature/commercialize-product
```

## 2) Activar GitHub Pages

1. En GitHub, abre el repositorio.
2. Ve a Settings > Pages.
3. En Build and deployment, selecciona:
   - Source: Deploy from a branch
   - Branch: feature/commercialize-product
   - Folder: /docs
4. Guarda cambios.

## 3) URL final para Play Store

Tu URL quedara asi:

```text
https://TU_USUARIO.github.io/TU_REPO/privacy-policy.html
```

Tambien funcionara:

```text
https://TU_USUARIO.github.io/TU_REPO/
```

(usa redireccion a privacy-policy.html).
