# Sistema de Gestión de Restaurante

## Estudiante

Ruth Noemí Arreaga Espinoza

## Descripción

Este proyecto corresponde a la Semana 6 de Programación Orientada a Objetos. El sistema administra productos de un restaurante mediante una estructura modular, aplicando herencia, encapsulación y polimorfismo.

## Estructura

```
Repositorio GitHub
├── restaurante_app/
│   ├── modelos/
│   │   ├── __init__.py
│   │   ├── producto.py
│   │   ├── platillo.py
│   │   └── bebida.py
│   ├── servicios/
│   │   ├── __init__.py
│   │   └── restaurante.py
│   └── main.py
└── README.md
```

## Herencia

La clase `Producto` actúa como clase padre, mientras que `Platillo` y `Bebida` heredan sus atributos y métodos mediante `super()`.

## Encapsulación

El atributo `__precio` se encuentra encapsulado y solo puede accederse mediante `obtener_precio()` y modificarse mediante `cambiar_precio()`, validando que el precio sea mayor que cero.

## Polimorfismo

El método `mostrar_informacion()` es sobrescrito en `Platillo` y `Bebida`, permitiendo que cada objeto muestre información específica al recorrer la lista de productos.

## Reflexión

En esta actividad comprendí que la herencia permite reutilizar código, la encapsulación protege la información importante del sistema y el polimorfismo facilita que diferentes objetos respondan de manera distinta utilizando un mismo método. Estos principios hacen que los programas sean más organizados, reutilizables y fáciles de mantener.