# Examen Cod
## Patron Factory

#### El patron builder de caracteriza por deparar el objeto de su representacion
#### Esto permitira crear diferentes representaciones para un solo objeto.
#### Un ejemplo de Patron Builder puede ser cualquier personalizacion desde comprarte unas zapatillas hasta un coche.
#### Ya que estos permitiran muchos colores, tamaños, pueden ser mas o menos deportivos.
### Diagrama de clases:
#### Voy a utilizar el ejemplo de coches.
```mermaid
classDiagram
    class Coche {
        -color: String
        -modelo: String
        -tipoMotor: String
        -tipoTrasmision: String
        -tipoAsientos: String
        +setColor(color: String): void
        +setModelo(model: String): void
        +settipoMotor(engineType: String): void
        +settipoTrasmision(transmissionType: String): void
        +settipoAsientos: String): void
        +getDescripcion(): String
    }
```

