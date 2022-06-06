# Redis-Node

• 1° paso: Instale redis
• 2° paso: Instale express, para tener un servidor básico
• 3° paso: Instale nodemon
• 4° paso: Realice una peticion mediante axios
• 5° paso: Despues de realizar unas pruebas, para ver el tiempo que tarda para obtenerlo, utilizo el modulo response-time.
           La respuesta es visualizada en X-Response-Time.
• 6° paso: Me conecte a redis mediante el host (bd de redis local) y port (6379).
           Redis solo guarda string, entonces para convertir un objeto a string utilizo el método JSON.stringify.
• 7° paso: Instale redis commander para ver lo que guarde en redis.
• 8° paso: Instale REST CLIENT (extension) para poder realizar llamadas HTTP desde visual.
• 9° paso: Realice dos pruebas diferentes para obtener personajes.
           Estas peticiones se guardan en redis, para poder disminuir el tiempo de busqueda.
