# COSES A FER EMPRESA 1
### Nivell 2:
- (FET) Creació VLANs per cada departament necessari a cada switch + PLCs, Seguretat, Climatització i Xarxa sense fils

- (FET) Trunk ports per 802.1Q (https://www.youtube.com/watch?v=GDAdQNf87hU)
  - Trunk Ports estan configurats als links entre switches en els que hem de transportar informació entre múltiples VLANS
  - Quan transmet informació d'una VLAN a una altra, afegeix el tag amb el ID de VLAN destí
  - El switch receptor només redireccionarà el tràfic d'informació als ports d'aquesta VLAN
  - Quan s'envia la trama a un port d'accés, s'elimina el tag .1Q amb l'ID de VLAN
  
  Cal mencionar i afegir la VLAN nativa, la qual és la VLAN a la que el switch enviarà dades sense etiquetar:
  - La VLAN nativa es la VLAN 1
  - Per problemes de seguretat, s'acostuma a cambiar aquesta VLAN nativa per una que no es emprada
  
  
- Definir interfaces

- (FET) Configurar LPS a la VLAN de Seguretat

- (FET) Mirar com configurar Spanning Tree

- Fer l'esquema lògic

- Subnetting local

- Taules d'encaminament
