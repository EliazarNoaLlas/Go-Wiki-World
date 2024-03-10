# GoWiki

GoWiki es una aplicación simple de wiki escrita en Go (Golang). Permite a los usuarios ver, editar y guardar páginas wiki.

## Características

- **Ver Páginas**: Los usuarios pueden ver el contenido de las páginas wiki existentes.
- **Editar Páginas**: Los usuarios pueden editar el contenido de las páginas wiki.
- **Guardar Páginas**: Los usuarios pueden guardar las ediciones realizadas en las páginas wiki.

## Requisitos

- Go 1.16 o superior.

## Uso

1. Clona el repositorio:

    ```bash
    git clone https://github.com/EliazarNoaLlas/Go-Wiki-World.git
    ```

2. Navega al directorio del proyecto:

    ```bash
    cd gowiki
    ```

3. Inicia el servidor:

    ```bash
    go run wiki.go
    ```

4. Abre tu navegador web y ve a `http://localhost:8080`.
5. Para ver una pagina dirigete a la ruta `http://localhost:8080/view/pagina`.
   5.1 Si la pagina no existe te redireccionara a la ruta `http://localhost:8080/edit`.
6. Para editar una pagina dirigete a la ruta `http://localhost:8080/edit/pagina`.

## Contribuir

Si deseas contribuir al proyecto, sigue estos pasos:

1. Crea un fork del repositorio.
2. Clona tu fork: `git clone https://github.com/EliazarNoaLlas/Go-Wiki-World.git`
3. Crea una nueva rama para tu función: `git checkout -b nueva-caracteristica`
4. Haz tus cambios y confirma: `git commit -am "Agrega una nueva característica"`
5. Empuja la rama a tu fork: `git push origin nueva-caracteristica`
6. Crea un Pull Request en el repositorio original.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para obtener más información.
