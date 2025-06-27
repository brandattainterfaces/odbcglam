# Streamlit MySQL Filter App

Esta aplicación interactiva te permite consultar una base de datos MySQL con filtros de fechas, cuenta, usuario, empresa y más, exportando los resultados a Excel desde una interfaz construida con Streamlit.

## Requisitos

- Python 3.8 o superior
- Streamlit
- pandas
- mysql-connector-python
- xlsxwriter

## Instalación

```bash
git clone https://github.com/tu_usuario/streamlit-mysql-filter.git
cd streamlit-mysql-filter
cp .env.example .env
pip install -r requirements.txt
```

## Variables de entorno

Configura el archivo `.env` con tus credenciales de MySQL:

```
DB_HOST=your-database-host
DB_USER=your-username
DB_PASSWORD=your-password
DB_NAME=your-database-name
DB_PORT=3306
```

## Ejecución

```bash
streamlit run app.py
```

## Licencia

MIT License
