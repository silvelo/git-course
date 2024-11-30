- **base_repo.7z** contiene el repositorio base del apartado `trabajando con ramas`. Si se descarga y descomprime se puede utilizar para los siguientes apartados.

![repo_status](images/report_status.png)

- **base_repo_2.7z** contiene el repositorio básico con dos ramas. Si se descarga y descomprime se puede utilizar para los siguientes apartados.

![repo_status](images/report_status_2.png)

- **rebase_repo.7z** contiene el repositorio básico para rebase. Si se descarga y descomprime se puede utilizar para los siguientes apartados.

![repo_status](images/rebase_git.png)

Nota: Ten cuidado con el editor por defecto incluido en el repositorio. La configuración del editor la puedes cambiar con (dentro del repositorio):

```
git config core.editor code | nano | vim
```

o

```
git config core.editor "code --wait"
```

o

```
git config --unset core.editor
```

# CI/CD

- En la carpeta js-ci-cd se encuentra el modulo con la configuración para un proyecto javascript

  - eslint: Comprobación de código
  - prettier: Comprobar estilos en el código
  - husky: Manejar hooks de python
  - convetional-commits: Controlar los mensajes con formato convetional commits

- En la carpeta js-ci-cd se encuentra el modulo con la configuración para un proyecto python.

  - Flake8: Comprobación de código
  - Black: Arreglar automáticamente el código
  - pre-commit: Manejar hooks de python
  - commitizen: Controlar los mensajes con formato convetional commits
