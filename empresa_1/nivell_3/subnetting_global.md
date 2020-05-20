**Equips de xarxa: Ordre EA-PB, EA-P1, EA-P2, EB-P1, EB-P0-0, EB-P0-1**

|Nom|Num-PCs|Mascara|Xarxa|Broadcast|Rang|Rang Usat|
|---|---|---|---|---|---|---|
|Produccio|	69|		255.255.255.128|	172.16.10.0|	172.16.10.127|		.1 a .126|	.1 a .69|		
|Administracio|	34|		255.255.255.192|	172.16.10.128|	172.16.10.191|		.129 a .190|	.129 a .162|		
|Comercial|	41|		255.255.255.192|	172.16.10.192|	172.16.10.255|		.193 a .254|	.193 a .233|		
|PLC	|	39|		255.255.255.192|	172.16.11.0|	172.16.11.63|		.1 a .62|	.1 a .39|		
|Qualitat|	23|		255.255.255.224|	172.16.11.64|	172.16.11.95|		.65 a .94|	.65 a .87|		
|Expedicions|	11|		255.255.255.240|	172.16.11.96|	172.16.11.111|		.97 a .110|	.97 a .107|
|Equips de xarxa (RACKS)| 6 | 255.255.255.224| 192.168.5.0| 192.168.5.255| .1 a .255| .1 a .6|


Passos:

1 => Per cada nombre de PCs, busquem la quantitat de bits per poder representar aquell nombre.

2 => 2^(nombre de bits per representar el nombre de PCs) - 2.

3 => Les adreces s'incrementen en base a al pas 2.
