# The PLC-PCB
The aim of the circuit board was to create a simple and inexpensive system. It is designed to give learners an insight into the basic structure and functioning of a PLC.
Together with the open source software OpenPLC, it provides an introduction to the world of PLCs.   


## The Schematic

### Connection of the ESP Board
<img width="1545" height="1065" alt="image" src="https://github.com/user-attachments/assets/dc4812c3-131c-4949-b49c-8e16df8c67e5" />

### 8 digital Inputs  
<img width="1545" height="1065" alt="image" src="https://github.com/user-attachments/assets/2cc73fb9-d3a7-42f7-bea3-6ee7d362c9b0" />

### 8 digital Relais-Outputs  
<img width="1545" height="1065" alt="image" src="https://github.com/user-attachments/assets/2fbd6f38-955d-4796-b011-91994da9c330" />

<img width="1545" height="1065" alt="image" src="https://github.com/user-attachments/assets/9fe2c917-ef84-4c56-8a60-eea09823eeb3" />

### 24V -> 5V Powersupply
<img width="1545" height="1065" alt="image" src="https://github.com/user-attachments/assets/8b1d77f8-ef1f-4b1d-b02d-52b7264869f4" />

## PCB
<img width="1014" height="657" alt="image" src="https://github.com/user-attachments/assets/68e0401b-cc41-4d2b-a26d-a42bf37dcfd6" />


## BOM
|	Count	|	Part	|	Value	|	Device	|	Footprint Name	|
|	-----	|	-----	|	-----	|	-----	|	-----	|
|	1 |	C1, C3	|	470µF	|	CPOL-EUUD-8X10	|
|	2 |	C2, C5	|	100nF	|	C-EUC0805	|	C0805	|
|	8 	|	D0	|	1N4148W	|	DIODE_1N4148W-7-F_SOD123G	|	SOD3715X135	| 
|	4 	|	J1	|	2601-1104CONN4_2601-1104_WAG	|	2601-1104CONN4_2601-1104_WAG |	CONN4_2601-1104_WAG	|
|	1 	|	J5	|	2601-1102CONN2_2601-1102_WAG	|	2601-1102CONN2_2601-1102_WAG |	CONN2_2601-1102_WAG	|
|	8   |	D10	|	SK34SMA	|	ZENERDO-214AC(SMA)	|	DIOM5226X290N	|
|	8 	|	JP1	|		|	PINHD-1X1	|	1X01| 
|	8 	|	K0	|	G5L	|	G5L	|	G5LE	|
|	1	|	L1	 |	47µH	|	L_CDRH127	|	IND_CDRH127/LDNP-470MC_SUM	|
|	1 	|	L3V3	|		|	LEDCHIPLED_0805	|	CHIPLED_0805	| 
|	1	|	L5V	|		|	LEDCHIPLED_0805	|	CHIPLED_0805	| 
|	1	|	L24V	|		|	LEDCHIPLED_0805	|	CHIPLED_0805	| 
|	LED0	|		|	LEDCHIPLED_0805	|	CHIPLED_0805	| 
|	8	|	LQ0	|		|	LEDCHIPLED_0805	|	CHIPLED_0805	| 
|	8 	|	OK0	|	LTV817S	|	LTV816S	|	DIL4-SMD	| 
|	8   |	OKQ0	|	LTV817S	|	LTV816S	|	DIL4-SMD	|
|	8	|	R0	|	15k	|	R-EU_R0805	|	R0805	| 
|	1 |	R10	|	470	|	R-EU_R0805	|	R0805	| 
|	1 	|	R11	|	4k7	|	R-EU_R0805	|	R0805	| 
|	8 	|	RQ0	|	2k2	|	R-EU_R0805	|	R0805	| 
|	8 	|	RQL0	|	2k2	|	R-EU_R0805	|	R0805	| 
|	8 	|	RU0	|	10k	|	R-EU_R0805	|	R0805	| 
|	1	|	U$1	|	ESP32DEVKITC	|	ESP32DEVKITC	|	
|	1	|	U2	|	TS2596	|	LM2596S-12/NOPBKTT0005B	|	
|	8	|	XQ0	|	1751251	|	1751251	|	1751251	| 
