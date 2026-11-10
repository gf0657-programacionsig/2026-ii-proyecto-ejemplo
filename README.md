# Cantones de Costa Rica: población y territorio, 2022

**Autor:** Manuel Vargas

Ejemplo del [proyecto final](https://gf0657-programacionsig.github.io/2026-ii/proyecto-final/) del curso GF-0657 Programación en SIG (II ciclo 2026), Escuela de Geografía, Universidad de Costa Rica. Es una aplicación interactiva de [streamlit](https://streamlit.io/) que muestra la población, el área y la densidad de los cantones de Costa Rica en 2022, junto con los aeródromos ubicados en ellos. Tiene filtros por provincia y por población mínima, tres indicadores, una tabla que puede descargarse, un gráfico de barras de plotly y un mapa de coropletas de folium que responde a los clics. Es la misma aplicación que se desarrolla en el cuaderno [streamlit: aplicaciones web interactivas](https://gf0657-programacionsig.github.io/2026-ii/streamlit-aplicaciones-web/).

## Aplicación publicada

Pendiente: la aplicación se publica en Streamlit Community Cloud durante la clase y su dirección se agrega aquí.

## Archivos

- [app.py](app.py): la aplicación.
- [requirements.txt](requirements.txt): las bibliotecas que la aplicación importa, con la versión fijada.

Los datos se cargan desde el [repositorio del curso](https://github.com/gf0657-programacionsig/2026-ii/tree/main/datos) mediante sus direcciones *Raw*, por lo que este repositorio no tiene carpeta `datos/`.

## Ejecución local

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Fuentes de los datos

Instituto Geográfico Nacional. (s. f.). *Límite cantonal 1:5000* y *Aeródromos 1:5000* [Conjuntos de datos]. Sistema Nacional de Información Territorial. https://www.snitcr.go.cr/

Instituto Nacional de Estadística y Censos. (2023). *Resultados Estimación de Población y Vivienda 2022* [Conjunto de datos]. INEC. https://admin.inec.cr/sites/default/files/2023-11/reResultadosEstimacionPoblacionVivienda2022_3.xlsx

## Uso de inteligencia artificial

La aplicación se escribió con la ayuda de Claude Code (Anthropic), que se usó para generar y depurar el código de `app.py`. El autor revisó todo el código y verificó las cifras que muestra la aplicación contra los datos originales.
