# Resistência em função da temperatura, materiais condutores e semicondutores 

Nesse projeto, vamos estudar a [resistividade](https://pt.wikipedia.org/wiki/Resistividade) de materiais [condutores](https://pt.wikipedia.org/wiki/Condutor_el%C3%A9trico) e [semicondutores](https://pt.wikipedia.org/wiki/Semicondutor),e seu comportamento com o aumento da temperatura. Se tratando de materiais condutores, a resistividade aumenta com o aumento da temperatura, isso acontece principalmente por causa do aumento das vibrações térmicas ([fônons](https://pt.wikipedia.org/wiki/F%C3%B4non)) da rede. No caso de semicondutores a resistência elétrica tende a diminuir porque o aumento da temperatura causa o aumento da concentração de elétrons na camada de condução.

A resistividade elétrica é uma característica intrínseca de cada material, e quantifica a oposição que ele causa no fluxo de corrente elétrica quando se aplica uma diferença de potencial. Quanto mais alta a resistividade elétrica, menos corrente passará pelo material. 

Para materiais uniformes e isotrópicos, podemos definir a resistência elétrica R do material a partir da resistividade elétrica.¹ Sendo a resistência o termo de proporcionalidade entre a tensão aplicada em um material e a corrente que passa por ele, na famosa [Lei de ohm](https://pt.wikipedia.org/wiki/Lei_de_Ohm). O fato que estudaremos aqui, que a resistividade varia com a temperatura, implica que a lei de ohm não é válida sempre (a menos que você considere que o termo de proporcionalidade não é constante), pois a passagem de corrente em um material varia sua temperatura.

![eq1](https://i.imgur.com/6ZeAML8.png)

A resistividade é usada para classificar os materiais em condutores, semicondutores ou isolantes, pois esta é uma característica intrínseca de cada material, e não depende de sua forma, como a resistência R mostrada na equação 1.

## Coleta dos dados

A coleta dos dados, foi realizada no laboratório de Física da Universidade Federal de Minas Gerais, e um vídeo foi disponibilizado para os alunos da disciplina Física experimental A3.

Um forno foi utilizado para aquecer o material estudado. O forno tem duas entradas, uma para colocar o termômetro digital e outra para o material medido.

A resistência R de um fio de platina (condutor) foi medida em função da temperatura, de 25°C​ até ​220°C, a cada 5°C.  O procedimento foi repetido utilizando agora o arsenieto de gálio (semicondutor), com a temperatura variando de 40°C a 220°C, iniciamos com uma temperatura mais alta neste caso pois para temperaturas menores que 40°C, o valor da resistência era muito elevado e o dispositivo utilizado não era capaz de medi-lo. 

Os resultados obtidos para o fio de platina (condutor) e para o arsenieto de gálio (semicondutor) encontram-se na pasta experimento, respectivamente nos arquivos platina.xlsx e GaAs.xlsx.

![potencial_periódico](https://i.imgur.com/PDHYXAk.png)

**Figura 1:** Imagem da uma medida realizada, para o fio de platina. O analógico 1 mede a temperatura através de um termopar que converte a temperatura em uma medida de tensão, 0.01 V representa 1ºC. Sendo assim a temperatura medida neste caso particular foi 85ºC (de acordo com a medida no analógico 1, 0.85V), a medida da resistência foi ​131 ohm.

## Descrição teórica do problema

Uma forma de obter a resistividade em função de propriedades de cada material, é modelando os elétrons que conduzem a eletricidade, como partículas livres sujeitas a um potencial periódico causado por íons positivos. Nesse modelo os íons são os átomos do material, que a grosso modo perderam elétrons (partículas livres) para a rede cristalina. Considerando uma rede cristalina infinita, este modelo fornece como resultado, que a energia permitida para os elétrons livres formam níveis contínuos de energia (chamados bandas permitidas), e estes níveis são separados também por níveis contínuos de energia (chamados bandas proibidas). A separação entre duas bandas de energia permitidas, é chamado de gap de energia, e este resultado pode ser visualizado na figura 2, para um potencial periódico unidimensional.¹

![potencial_periódico](https://i.imgur.com/dnaF8Um.png)

**Figura 2:** (a) Potencial de energia periódico unidimensional, ao qual um elétron está sujeito. (b) Solução dos níveis de energia do elétron, em função do seu número de onda k.¹

O resultado exibido na figura 2, mostra que para um elétron estar livre para conduzir eletricidade, ele precisa adquirir energias específicas. Os elétrons mais propensos a se tornarem livres na rede, são os elétrons da [camada de valência](https://pt.wikipedia.org/wiki/Camada_de_val%C3%AAncia). Denominando então a banda ocupada pelos elétrons da camada de valência, como banda de valência, e a [banda de condução](https://pt.wikipedia.org/wiki/Banda_de_condu%C3%A7%C3%A3o#:~:text=Banda%20de%20condu%C3%A7%C3%A3o%20%C3%A9%20a,relativa%20liberdade%20pelo%20material%2C%20logo%2C) como a primeira banda permitida logo acima, vemos que quando a banda de condução se superpõe com a banda de valência, os elétrons facilmente se desprendem dos átomos, tornando-se livres para conduzirem eletricidade, este é o caso dos condutores. No caso dos semicondutores, existe uma pequena diferença entre a banda de condução e a banda de valência, de forma que esta diferença pode ser fornecida por agitação térmica em temperaturas razoáveis. Por último, para o caso dos isolantes a diferença de energia é mais elevada ( >2eV).¹

Analisando a resistividade , e a [condutividade elétrica](https://pt.wikipedia.org/wiki/Condutividade_elétrica) (inverso da resistividade), em termos da descrição quântica dos elétrons livres, é possível chegar na equação 2.¹

![eq2](https://i.imgur.com/u9xAyCf.png)

O [princípio de exclusão de Pauli](https://pt.wikipedia.org/wiki/Princ%C3%ADpio_de_exclus%C3%A3o_de_Pauli) assume um papel importante aqui, este princípio afirma que dois elétrons próximos não podem assumir o mesmo estado quântico, este fato diminui a quantidade de elétrons que podem ocupar uma dada banda de energia, fazendo com que os elétrons sigam a [distribuição de Fermi-Dirac](https://pt.wikipedia.org/wiki/Estat%C3%ADstica_de_Fermi-Dirac), descrita na equação 3, sendo a [energia de Fermi](https://pt.wikipedia.org/wiki/Energia_de_Fermi) o último nível de energia ocupado por um elétron livre a temperatura de 0 K. O termo n que aparece na equação 2, deve ser proporcional a f(E) descrito na equação 3 (como mostra a equação 4), para a energia a energia que o elétron deve possuir para estar na camada de condução. No caso dos condutores nenhuma energia deve ser obtida, sendo assim o valor n permanece quase constante com a temperatura. Por outro lado, para os semicondutores uma certa energia deve ser obtida pelo elétron para ele chegar a banda de condução, fazendo com que a resistividade varie com a temperatura de acordo com a expressão descrita em 6 (válida apenas para materiais semicondutores).¹

![eq3a6](https://i.imgur.com/wZ8BUWn.png)

Esta forma em que chegamos para a equação 6 é conhecida como [lei de Arrhenius](https://pt.wikipedia.org/wiki/Equa%C3%A7%C3%A3o_de_Arrhenius), e descreve um processo termicamente ativado, ou seja, apenas para uma temperatura suficientemente grande R assume valores razoáveis, de forma que o material conduza eletricidade, por outro lado, para temperaturas pequenas R é muito grande e ele se comporta como isolante, a não ser que outra fonte de energia seja utilizada para excitar os elétrons para a banda de condução.

O termo do livre caminho médio que aparece na equação 2, também depende da temperatura, mas de forma linear como descrito na equação 7, ou seja, no caso do semicondutor o termo que decresce exponencialmente com a temperatura prevalece, mantendo válida a equação 6. Já no caso dos condutores, vimos que o termo exponencial não aparece, e o termo linear que surge por conta do livre caminho médio prevalece, gerando a equação 8, que mostra como a resistividade  deve variar com a temperatura, para o caso dos condutores.

A equação 7 pode ser obtida, calculando o livre caminho dos elétrons através do desvio dos íons da rede em torno da posição de equilíbrio, modelando os íons como pontos vibrando na rede por agitação térmica.¹

![eq7a8](https://i.imgur.com/t30Y2Z5.png)

Chegamos em resultados bem distintos, para o comportamento que a resistência de um material deve ter variando a temperatura, dependendo se o material é um condutor ou um semicondutor. No caso dos condutores, a equação 8 mostra que devemos esperar que a resistividade aumente linearmente com a temperatura, ja no caso dos semicondutores a equação 6 nos mostra que devemos esperar uma queda exponencial da resistividade com a temperatura. Analisando os dados obtidos para o fio de platina (condutor) e para o arsenieto de gálio (semicondutor), foi possível confirmar as previsões teóricas, a análise foi feita utilizando a linguagem de programação Python e se encontra na pasta experimento, no arquivo análise.ipynb. 

## Referência

**¹** PAUL A., Tipler; RALPH A., Llewellyn. Modern Physics, Chapter 10. 6. ed. [*S. l.*: *s. n.*], 2012.