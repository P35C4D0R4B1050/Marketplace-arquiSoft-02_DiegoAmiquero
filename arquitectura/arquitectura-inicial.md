```mermaid
graph TD
    %% Configuración de estilos visuales para asemejarse a la imagen
    style PRESENTACION fill:#1e1e1e,stroke:#fff,stroke-width:1px,color:#fff;
    style LOGICA fill:#1e1e1e,stroke:#fff,stroke-width:1px,color:#fff;
    style DATOS fill:#1e1e1e,stroke:#fff,stroke-width:1px,color:#fff;
    linkStyle 0,1 stroke:#fff,stroke-width:1px;

    PRESENTACION["<b>PRESENTACIÓN</b><br>Web / API / Interfaz"]
    
    PRESENTACION --> LOGICA

    LOGICA["<b>LÓGICA DE NEGOCIO</b><br><br>Catálogo<br>Carrito<br>Pedidos<br>Sellers<br>Usuarios"]
    
    LOGICA --> DATOS

    DATOS["<b>DATOS</b><br>Base de datos"]
```
