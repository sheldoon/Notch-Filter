# Notch-Filter

O projeto proposto consistia em aplicar os conhecimentos adquiridos em sala de aula
para filtragem digital de sinais. No caso específico, projetar um filtro digital para a remoção de
ruídos (aliasing) de um sinal de eletrocardiograma. Para isso, conhecimentos de Python e suas
bibliotecas, tipos de filtros e seus parâmetros (Resposta em frequência - RF, coeficientes,
ordem, frequências de amostragem e corte, entre outras características de filtros), além de
análises de viabilidade na construção do filtro digital escolhido.
#

Inicialmente, do sinal ECG ruidoso, foi escolhida a sequência s4 como amostra do sinal
a ser filtrado:

![image](https://user-images.githubusercontent.com/84822895/210431395-73b27567-48bd-4758-8c8e-78caef16e836.png)

Após o processo de filtragem, foi possível chegar no seguinte sinal:

![image](https://user-images.githubusercontent.com/84822895/210431629-ead948c8-43a4-4987-95ce-6387319b3aa1.png)
#

- O sinal foi extraido do arquivo <a href="https://github.com/sheldoon/Notch-Filter/blob/main/ECGruidoso.mat">ECGruidoso.mat</a>
- O código utlizado na filtragem do sinal pode ser visto ao clicar <a href="https://github.com/sheldoon/Notch-Filter/blob/main/ECG_notch.ipynb">aqui</a>


