# Paso 2: Clonar y Abrir en VS Code

1. Copia la URL del repositorio (`Code > HTTPS`).
2. Abre la terminal y ejecuta:

```bash
git clone https://github.com/tu_usuario/calculadora-js.git
cd calculadora-js
```

3. Abre VS Code con:

```bash
code .
```

4. creamos el archivo `calculadora.js`
```bash
touch calculadora.js
```

5. lo agregamos para que `GIT` le haga seguimiento, luego confirmamos el cambio con `commit`
```bash
git add calculadora.js
git commit -m "subida inicial"
```

6. subimos los cambios al repositorio en github
```bash
git push origin main
```


[Anterior](01-crear-repo.md) | [Siguiente: Crear una rama y añadir la calculadora »](03-rama-calculadora.md)
