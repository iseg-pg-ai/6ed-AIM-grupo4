1. Aplicar a TELOS ao projeto como filtro prévio. (Ponto 2)



2. Criticar o problem statement
	- Existem muitas fontes de dados;
	- Conseguir prever falhas nos switches não resolve os problemas da empresa se as equipas de manutençao 
		**INTERNAS** não forem suficientes para colmatar todas as falhas em tempo util;

3. Criticar os expected benefits do CEO
	- 99,99% de accuracy é irrealista, valores realistas seriam entre 85% e 95%, e seriam necessários pelo menos 4 modelos,
		 um para cada periodo temporal, com accuracies diferentes;
	- Poupar pelo menos 2 Milhões é possivel sob as seguintes condições:
		- Custo de trabalho planeado = 500
		- Custo de incidente não planeado = 5000
		- Diferença = 5000 - 500 = 4500
	 	- 2.000.000€ / 4500 = 445
		- Evitando aproximadamente 445 incidentes não planeados, convertendo-os em manutenções planeadas.
		- isto é apenas relevante se 445 incidentes não planeados já ocorrerem anualmente.
	- Dizer ao CEO que nao deve colocar um limite maximo nas poupanças possiveis da empresa
	- 

5. Additional Information to ask the company
	Tipo / quantidade de switches/rails que temos / existem (Dimensao do universo)
	Registo historico anual de manutençoes programadas e nao programadas
	Que tipo de dados vêm dos IoT?
		- Viaturas
			- Numero de veiculos que passam diariamente / por hora no switch (Intensidade de trafego)
			- Peso
			- Velocidade
		- Carris
			- Temperatura
			- Humidade
			- Vibração
			- posiçao GPS



Notas:

4. Assunção:
- Falsos Positivos:
	- Em caso de falso positivo em manutençao preventiva, ao inves de custar 500€, 
	custa 400€ (Deslocações, Tempo dos técnicos), poupando-se os outros 100€ (Materiais)
