# Run server:

### 1. localhost

1. Start a `cmd` terminal in the directory.


2. Run local server with command: 

    `
    python -m http.server
    `

    or 

    `python -m http.server <custom port>`


### 2. Own network

1. Start a `cmd` terminal in the directory.

    - run  `ipconfig`

    - check: Ethernet adapter Ethernet (IPv4 Address)

    - run in `cmd` terminal `python -m http.server 9999 -b <IPv4 Address>`


        `GET  http://<IPv4 Address>:9999/`

        `POST http://<IPv4 Address>:9999/`



