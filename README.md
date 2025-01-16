
# Consultas MongoDB - Óptica

📄 **Descripción**  
Este proyecto contiene ejercicios de MongoDB relacionados con la gestión de datos de una óptica. Las colecciones incluyen información sobre clientes y gafas, con detalles como compras realizadas, proveedores y empleados.

---

💻 **Tecnologías Utilizadas**  
- MongoDB  
- JSON para la representación de datos  

---

📋 **Requisitos**  
- MongoDB instalado y en ejecución  
- Terminal o MongoDB Compass para ejecutar las consultas  

---

🛠️ **Instalación**  
1. Clona el repositorio:  
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   ```
2. Importa los conjuntos de datos en tu instancia de MongoDB:  
   ```bash
   mongoimport --db optica --collection customers --file optica.customer.json
   mongoimport --db optica --collection glasses --file optica.glasses.json
   ```

---

📁 **Estructura del Proyecto**  
- `optica.customer.json`: Archivo JSON con los datos de los clientes de la óptica.  
- `optica.glasses.json`: Archivo JSON con los datos de las gafas y proveedores.  

---

📚 **Documentación**  
Para más información sobre la sintaxis de consultas y operaciones de MongoDB, consulta la [Documentación Oficial de MongoDB](https://www.mongodb.com/docs/).
