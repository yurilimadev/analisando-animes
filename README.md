# Analisando Animes e Mangás

<center>
  
  ![personagens-de-animes-10](https://github.com/yurilimadev/analisando-animes/assets/108006649/5f081091-a54a-40d7-bf88-d62091dcd95a)
  
</center>

<p>Quando estamos em busca de uma carreira profissional, sonhamos em trabalhar com algo que nós gostamos ou pelo menos que tenhamos afinidade. "Trabalhe com o que goste e não vai trabalhar um dia se quiser na vida." é o que dizem. Bem, eu acho que isso é uma meia verdade, pois não condiz com a realidade de muitas pessoas. Muito provalvemente, existem muitas pessoas que não estão trabalhando hoje com o que amam. Contudo, quando existe a possibilidade de algo que nós gostamos se cruzar com a nossa profissão, temos que agarrar essa oportunidade. E foi o que aconteceu comigo.</p>
<p>Eu estou participando de um programa de imersão para me adequar a vida de Dev. E durante trinta dias, aprendemos os 5 pilares para ser um bom profissional, como ter compromisso com o aprendizado, aprender a se virar e entregar um projeto, basicamente, toda a semana. Eu gosto muito da área de dados e estou me desenvolvendo cada a vez mais com o tratamento de dados e escolhas dos parametros necessários para uma análise exploratória que traz insights bem bacanas. E estou desenvolvendo meu terceiro projeto. O primeiro tinha a ver com carros, o segundo com a minha faculdade de farmácia...</p>
<h2>mas, aconteceu...</h2>
<p>Enquanto buscava qual o seria o tema do meu próxmio projeto nas diversar bases de dados encontrei um sobre animes e mangás. Eu fiquei maravilhado e intrigado. Maravilhado por ser sobre um assunto que tenho um carinho enorme e intrigado, pois ainda tenho uma voz na minha cabeça que diz que não pode sair uma análise séria e profissional sobre animes e mangás. Eu acho que essa voz gosta de estar errada. 
</p>
<p>Se eu posso dizer o que eu aprendi com essa experiência foi como pode ser divertida a exploração de dados de quaisquer tipos. Nessa base de dados disponibilizada pela kaggle, temos informações sobre animes e mangás em dois arquivos csv. Lá temos as informações básicas de qualquer produção literária quanto audiovisual. Contudo, decidi focar mais na base de dados de animes e fazer breves comparações com a base mangás. Isso até foi um escolha feliz, pois muitos animes não tinham sua correspondência na base de dados de mangás, sendo apenas <strong>11,66%</strong>presentes.</p>
<h2>Quais os tratamentos feitos</h2>
<p>A base de dados de animes teve que passar por alguns tratamentos de dados que fosse possível pensar em uma estratégia para iniciar a exploração de dados. Tive que remover animes que não possuiam números de epiósidio e tipo. Mas, um fato interessante é que o anime com o tipo desconhecido parace ser uma versão japonesa de o Mágico de OZ ou que contenha um compilado de histórias clássicas.</p>

![download](https://github.com/yurilimadev/analisando-animes/assets/108006649/714612b4-f9e6-4b8a-ab78-b4e0de0b40d7)

<p>E por fim, o campo que representa as datas de exibição estão dispostas em períodos e o que foi feito para tratar essa situação essa coluna foi dividida em duas: Data_Inicio e Data_Fim.</p>

<h2>A Exploração de Dados</h2>
<p>Eu gosto de explorar os dados depois de fazer um breve relatório simples com as frequências relativas dos dados, assim, tenho uma noção do esperar do comportamento do dados e entender se são numéricos ou categóricos. Dessa forma, desenvolvi as seguintes perguntas: </p>

* Quais os cinco animes mais bem posicionados?
* Quais os cinco animes com as piores posições?
* Dos animes que passavam na TV quais tinham mais episódio?
* Quantos animes tiveram 1 episódio? Eles eram todos filmes? Qual foi a melhor filme da base de dados?
* O que são OVAs e ONAs? Quais dessas duas categorias tiveram mais episódios?
* Qual OVA teve a melhor nota de rank?
* O número de pessoas envolvidas na produção do anime tem correlação com as sua qualidade em relação ao público?
* Qual o período que teve mais lançamento de animes dentro dessa base de dados?
* A qualidade dos animes, de acordo com essa base de dados, tem aumento ou diminuido?
* Quais desse animes aparecem na base de dados de mangá?

<p>Ficou interessado em saber quais as respostas que eu consegui? Dá uma olhada no notebook completo que está nesse repositório, mas eu já mostro aqui os insights mais interessantes dessa análise.</p>
<h2>Os cinco animes mais bem avaliados</h2>

![download](https://github.com/yurilimadev/analisando-animes/assets/108006649/deac5e49-1f54-422f-bfb6-6845b842bb6f)

Confesso que não esperava menos já que o meu anime favorito está na primeira posição. ❤️

<h2>Quais os cinco animes com as piores posições?</h2>

![download](https://github.com/yurilimadev/analisando-animes/assets/108006649/085e1b8c-b873-4943-bcd9-313524f162b2)

<p>Esse aqui eu acho que vão deixar as pessoas mais intrigadas porque todo mundo quer saber o porquê de um produção ser tão ruim. E fiquei bem chocado com a arte das imagens desse cinco piores animes. Fiquei com o sentimento de "O que é isso, meu deus!?"</p>

<h2>Original Video Animation com melhor nota</h2>

![download](https://github.com/yurilimadev/analisando-animes/assets/108006649/911fe449-8843-42ab-845c-8ecfa6f95482)

Mais um anime que eu não fazia a menor ideia que existia e que só está me deixando mais curioso e você? 

<h2>Qual o período que teve mais lançamento de animes dentro dessa base de dados?</h2>

![download](https://github.com/yurilimadev/analisando-animes/assets/108006649/ad63bd81-b868-4f2e-bbf9-040ea5c138e0)

Esse dado eu achei interessante, podemos perceber que no japão já existia produções que eram consideradad animes no início do século XX, mas o periódo que mais teve lançamento de animes foi em 2019 e teve uma breve queda em 2020, até o período de 2023. Isso pode ter isso impacto da pandemia do COVID-19 que impactou toda a economia mundial e a industria otaku não saiu ilesa. Mas, não é possível afirma que daqui em diante a produção não aumente ou permaneça a mesma, pois não temos dados dos próximos meses de 2023.

<h2>O número de espectadores do anime tem correlação com as sua qualidade em relação ao público?</h2>

![download](https://github.com/yurilimadev/analisando-animes/assets/108006649/e4ad29c3-79b2-45c2-a423-9dff15c1dfad)

Essa eu esperava que sim, mas estava análisando da forma errada. Na base de dados disponibilizada pela kaggle, a coluna de espectadores estava sendo analisada como de membros da produção. E se espera que com mais membros a produção tenha uma qualidade melhor, mas isso não necessáriamente é verdade. Contudo, a questão a ser a analisada está relacionado com a fan base do anime. E não. A correlação é de 0.40, a qual é muito baixa para afirmar que possa existir uma proporcionalidade envolvida entre o número de espectadores. Mas, achei a dúvida justa, pois quanto mais o fandom maior o apoio e também o ódio. 

<h1>Conclusão</h1>
Com base na análise realizada dos dados de animes e mangás, podemos chegar a algumas conclusões interessantes.

Primeiramente, foi uma experiência enriquecedora explorar dados relacionados a um tema que tenho grande afinidade, como animes e mangás. Isso mostrou o quanto a exploração de dados pode ser divertida e revelar insights valiosos sobre um assunto que nos interessa.

Observamos que os cinco animes mais bem avaliados são produções de alta qualidade, o que não é surpreendente, pois animes populares tendem a receber mais atenção e reconhecimento do público.

Por outro lado, os cinco animes com as piores posições nos deixam intrigados, e a arte dessas produções pode ser motivo de surpresa e até mesmo perplexidade. Isso mostra que nem todas as produções podem atender às expectativas do público.

Também identificamos que os OVAs (Original Video Animations) são mais frequentes e têm mais episódios do que os ONAs (Original Net Animations), indicando que OVAs são mais comuns em comparação com ONAs.

Quanto ao período com maior lançamento de animes, notamos um aumento significativo em 2019, seguido por uma leve queda em 2020 até o período de 2023. Isso pode ser influenciado pela pandemia do COVID-19, que afetou diversas indústrias, incluindo a indústria de animes.

Ao investigar a correlação entre o número de espectadores e a qualidade do anime, descobrimos que a correlação é baixa (0,40), sugerindo que não há uma relação direta entre o número de espectadores e a qualidade do anime. Isso pode ser explicado pelo fato de que o sucesso de um anime não está diretamente ligado ao número de membros da equipe de produção, mas sim ao apoio e à reação do público em geral.

Em suma, essa análise dos dados de animes e mangás nos permitiu obter insights valiosos sobre esse universo, e percebemos que a exploração de dados pode ser aplicada a qualquer tema com resultados interessantes. A combinação de nossa paixão e habilidades profissionais pode nos levar a oportunidades incríveis, como essa experiência com análise de dados de animes, que nos proporcionou uma visão ainda mais profunda e gratificante do universo otaku.

<h1>Contato</h1>
Email: dimitri.limaf@gmail.com
LinkedIn: https://www.linkedin.com/in/yuri-lima-dev/
