<h1>Desafio: Calculadora de consumo de combustível – Processo seletivo Squad Software TMR</h1>

<p>Suponha que você está desenvolvendo um software para uma empresa de transporte de cargas que precisa calcular o consumo médio de combustível por tonelada transportada de sua frota de caminhões e apresentar através de uma aplicação web. Para isso, você precisa criar uma aplicação que realiza o cálculo de consumo de combustível a partir das informações de um veículo. Para isso, as seguintes informações deverão ser preenchidas pelo usuário:</p>  

 >Placa: uma string indicando a placa do veículo;  
 >Modelo: uma string indicando o modelo do caminhão;  
 > Capacidade do tanque: um número indicando a capacidade total do tanque de combustível do caminhão em litros;  
 >Carga máxima: um número indicando a carga máxima que o caminhão pode transportar em toneladas;  
 >Consumo médio: um número indicando o consumo médio de combustível do caminhão em litros por 100 km.  
 >Distância percorrida na jornada: um número indicando a distância média percorrida pelo veiculo em km. 

<p>A partir dessas informações, a aplicação deverá calcular o consumo médio de combustível por tonelada transportada pelo veículo, e apresentar de maneira legível para o usuário.</p>  

<p>Para calcular o consumo de combustível por tonelada, você deve seguir as seguintes etapas:    

<p>Para cada caminhão, calcular o peso médio transportado por km, considerando a carga máxima que o caminhão pode transportar e a distância média percorrida pela frota de caminhões. Para isso, você deve considerar que o peso médio transportado por km varia de acordo com a capacidade de carga de cada caminhão e a distância média percorrida pelo veículo. Por exemplo, se o veículo percorreu 1000km e um caminhão pode transportar até 10 toneladas de carga máxima, o peso médio transportado por km será de 10 / (1000 * 0,001) = 10 kg por km.  

<p>Para cada caminhão, calcular o consumo médio de combustível por tonelada transportada por km, dividindo o consumo de combustível por km pelo peso médio transportado por km. Por exemplo, se o consumo de combustível por km for de 1,75 litros e o peso médio transportado por km for de 10 kg, o consumo médio de combustível por tonelada transportada por km será de (1,75 * 1000) / (10 * 1000) = 0,175 litros por tonelada por km.  

<h2>Resultado esperado:</h2>
 
<p>Uma Aplicação Web com um formulário onde o usuário poderá preencher as informações de um veículo e obter o consumo médio de combustível por tonelada transportada.  
 
Bônus: A aplicação apresenta uma lista com histórico dos últimos cálculos que não é apagada ao recarregar a página. </p>

---
<h2>Regras</h2>
<br/>

1. A aplicação deverá ser desenvolvida utilizando ReactJS;  
2. Deve ser utilizada a biblioteca MaterialUI 5(https://mui.com/) para a estilização dos componentes;  
3. Deve ser utilizada a biblioteca Formik(https://formik.org/) para o formulário da aplicação.  
4. A aplicação deverá seguir o Brandbook da Intelbras: https://brandbook.intelbras.com/a-marca/  
5. O projeto deverá ser registrado em seu Github até o dia 09/10 às 17:00h e enviado para o e-mail: paulo.cora@intelbras.com.br 

---
