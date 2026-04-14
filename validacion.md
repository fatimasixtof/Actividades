"Validación del Modelo de Tráfico Fantasma"

¿Qué tanto se parecen las simulaciones al patrón empírico?

Las simulaciones logran reproducir de buena manera la dinámica macroscópica descrita por Tadaki. La gráfica generada exhibe las dos fases principales del diagrama fundamental del tráfico:

1\. Fase de flujo libre: A densidades bajas, la relación entre densidad y flujo es lineal y positiva; los autos pueden moverse a su velocidad máxima sin interrupciones.

2\. Fase congestionada (tráfico fantasma): Al cruzar un umbral de densidad crítica, el flujo cae abruptamente y comienza a oscilar. Esto ocurre porque la distancia entre vehículos se reduce, eso provoca que cualquier ligera desaceleración genere una reacción en cadena (una onda de choque hacia atrás) que obliga a los autos a detenerse casi por completo, reduciendo el flujo global del sistema, también lo vemos en la perturbación que genera que nuestro carro muestra desacelere en el experimento de la practica cuando estábamos en el caso "homogéneo".

¿Qué se le podría cambiar al modelo para obtener resultados que sean más similares a los datos empíricos?

Para acercar aún más la simulación a la realidad empírica, se podrían implementar las siguientes modificaciones:

Heterogeneidad en los conductores: Asignar diferentes tiempos de reacción, velocidades o aceleraciones, imagino que eso se podría hacer dando de forma aleatoria cierta velocidad mayor o menor a un porcentaje de los carros.

Carriles múltiples: Hacer carreteras y permitir el cambio de carril evaluando la conveniencia y seguridad espacial, lo cual disipa localmente las ondas de choque pero puede crearlas en carriles paralelos.
