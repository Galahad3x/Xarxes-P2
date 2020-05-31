# FALTA FER
- (FET) Arreglar esquema fisic empresa 1 (lacp i VLAN per defecte)
- (FET) Afegir lag a l'esquema fisic emp2
- (FET) Arreglar esquema logic nivell 3 empresa 1 ho faré jo Joel A quan tingui el png del moi a la nit
  - Arreglar encaminament empresa 1 Joel A
- Fer lo mateix amb l'empresa 2 (esquema fet)
- PDF informe Armand
- **ACABAR FASE 1**
- Empresa 1: Modificar subnetting, encaminament i (esquema niv3 FET) per afegir RNI (Joel A)
- Empresa 2 FASE 2:
  - (FET) Afegir VLANs a Assignació VLANs
  - Modificar esquema físic i lògic per afegir les VLANs per 802.1q
  - Modificar assignació de ports per a afegir els ports que siguin
  - Modificar creació VLANs nivell 2 per crear VLANs i passar-les per 802.1q, STP etc etc
## Poso aquest comentari per saber com modificar el esquema lògic
    Equips seguretat i climatització:
      ·Edifici 1:
        ·Planta baixa i planta 1: 2 equips de climatització i 3 equips de seguretat.
      ·Edifici 2:
        ·Planta baixa, primera platai planata segona: 2 equips de climatització i 3 equips de seguretat.
      ·Nau industrial:
        ·2 equips de climatització i 3 equips de seguretat.

- Empresa 2: Modificar vlans de nivell 2 per afegir el que faci falta (Joel A)
- Redactar merdes (Farre)

# Xarxes-P2
## Subnetting
- Les xarxes tenen la mateixa màscara a tots els racks  
- Ordre de l'adreçament en l'empresa 1: R-EA-PB,R-EA-P1,R-EA-P2,R-EB-P1,R-EB-P0-0,R-EB-P0-1  
  -L'empresa 1 tindrà 139 adreces sense utilitzar
- Ordre de l'adreçament en l'empresa 2: R-E1-PB,R-E1-P1,R-E2-PB,R-E2-P1,R-E2-P2,R-RNI  
  -L'empresa 2 tindrà 54 adreces sense utilitzar
## Encaminament
- Tots els routers tenen, com a adreça IP, l'adreça més alta possible.
