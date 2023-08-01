Run server:

### 1. localhost

1. Start a `cmd` terminal in the directory.


2. Run local server with command: 

    `
    python -m http.server
    `

    or 

    `python -m http.server <custom port>`


### 2. Own network


- run `cmd` terminal

- run  `ipconfig`

- check: Ethernet adapter Ethernet (IPv4 Address)

- run: `python -m http.server 9999 -b <IPv4 Address>`




