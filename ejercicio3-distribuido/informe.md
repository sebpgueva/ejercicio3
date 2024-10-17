# Informe de Entrega del Proyecto

## Objetivo del Proyecto
El objetivo de este proyecto es implementar un sistema distribuido con tolerancia a fallos utilizando Apache ZooKeeper, permitiendo la gestión eficiente de nodos y la redistribución de la carga ante fallos.

## Descripción Técnica del Sistema
Este sistema se desarrolla en Java y utiliza Apache ZooKeeper para la coordinación entre nodos. Implementa la creación y actualización de nodos, así como la simulación de fallos y la redistribución de carga.

## Pasos de Implementación
1. Configuración del entorno de desarrollo en GitHub Codespaces.
2. Creación de un proyecto Maven y configuración de dependencias.
3. Implementación de la lógica del sistema en la clase `App.java`.
4. Pruebas del sistema, incluyendo la creación y eliminación de nodos en ZooKeeper.

## Resultados de las Pruebas
Se realizaron pruebas exitosas para la creación, actualización y eliminación de nodos. La redistribución de carga funcionó correctamente al eliminar un nodo.

## Conclusiones sobre la Implementación
La implementación del sistema distribuido ha sido exitosa. Apache ZooKeeper demostró ser una herramienta efectiva para la gestión de nodos y la tolerancia a fallos. Se recomienda seguir explorando más funcionalidades de ZooKeeper para mejorar la resiliencia del sistema.
