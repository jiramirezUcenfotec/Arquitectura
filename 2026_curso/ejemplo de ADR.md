# authors - section only for the course
- Daniel Canessa Valverde
- Verny Alonso Alfaro M.
- Shirley Ramírez Cordero

# Title 
- Elección del protocolo de comunicación para los servicios JSON vs. GRPC.

# Status
- Propuesta

# Context
- El negocio solicita la reducción de costos de comunicación de servicios de la nube

# Decision
- Utilizar GRPC

# Consequences
- Pros: el trasiego de los datos es menor en bits transmitidos que JSON y que se traduce en un menor costo de trasiego de información.

- Contras: GRPC obliga al cliente/servidor a tener una comunicación tipada y fuertemente acoplada.

# Compliance
- Validado con una prueba de servicios en JSON vs GRPC.

# Notes
- enlace a pruebas
- https://es.wikipedia.org/wiki/JSON

