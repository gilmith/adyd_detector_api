Lo que hace con poe es tener casi un maven o u npm para ejecutar pasos y generar codigo.

Define las dependencias de los proyectos haciendo un add library 

Y con poe puede ejecutar task, en este caos la de openapi es de java o de node pero la puede ejecutar

el pyproject.toml es el equivalente al package.json de node para generar las dependencias del proyecto.

Para compilar poetry build

publicar en github packages 

poetry config repositories.github https://pypi.pkg.github.com/<ORGANIZACION>/adyd-contracts

poetry config http-basic.github <TU_USUARIO_GITHUB> <TU_TOKEN_PAT>

poetry publish --build -r github