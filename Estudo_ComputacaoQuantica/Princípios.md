
A [mecânica quântica](https://pt.wikipedia.org/wiki/Mec%C3%A2nica_qu%C3%A2ntica "Mecânica quântica") é considerada a mais bem sucedida teoria física. Pois desde a sua criação até os dias atuais, ela tem sido aplicada em diversos ramos, desde a [física de partículas](https://pt.wikipedia.org/wiki/F%C3%ADsica_de_part%C3%ADculas "Física de partículas"), atômica e molecular até a [astrofísica](https://pt.wikipedia.org/wiki/Astrof%C3%ADsica "Astrofísica") e matéria condensada.

Na computação quântica a unidade de informação básica é o [Bit quântico](https://pt.wikipedia.org/wiki/Bit_qu%C3%A2ntico "Bit quântico") ou q-bit. O fato da computação quântica ser tão poderosa está no fato de que além de assumir '0' ou '1' como na computação clássica, ela pode assumir ambos os estados '0' e '1' ao mesmo tempo. Parece estranho algo assumir os dois estados diferentes ao mesmo tempo, mas a experiência mental do Gato de Schrödinger pode dar um sentido intuitivo à situação. E é graças à essa propriedade da superposição de estados que motivou os estudos em computação quântica. Se na computação clássica o processamento é sequencial, na computação quântica o processamento é simultâneo.

Imagine que uma pessoa precise encontrar o contato de telefone de alguma pessoa em uma lista, na computação clássica é como se ela olhasse em cada nome conferindo se é o contato procurado. Já em um processamento quântico é como se uma pessoa conseguisse conferir vários nomes a cada processamento.

O q-bit é descrito por um vetor estados em um sistema quântico de dois níveis o qual é equivalente a um vetor de espaço bidimensional sobre [números complexos](https://pt.wikipedia.org/wiki/N%C3%BAmero_complexo "Número complexo"). Usa-se a notação de bra-ket para representá-los:

![[626a1534e007d6511762add99f012fbe7db8f845.svg]]

Assim, o estado de um q-bit pode ser representado por: ![[aabd1ffc6a57b00e254e4c212d98ebbea6ccc7fc.svg]], O conjunto ![[7a72099dd8347d05e92c98f19db855b1651f8402.svg]], forma uma base no espaço de Hilbert de duas dimensões, chamada de base computacional.

Para a manipulação dos estados quânticos utiliza-se principalmente técnicas ópticas, isto é radiação eletromagnética. Estes dispositivos constituem-se as portas lógicas quânticas. A manipulação pode ser realizada utilizando átomos que podem ser excitados ou não ou os dois ao mesmo tempo. Outro dispositivo utilizado é a manipulação de fótons. A vantagem em utilizá-los está no fato de que esses fótons podem constituir-se portadores altamente estáveis de informação quântica. Entretanto fótons não interagem diretamente entre si, sendo necessário o uso de um átomo como mediador, que introduz um ruído adicional e complicações no experimento. Neste caso um fóton interage com um átomo que por sua vez interage com o segundo fóton, levando à interação completa entre os dois fótons.

Para armazenar os q-bits utiliza-se armadilhas de íons (íon trap) em que um pequeno número de átomos carregados são aprisionados e armadilhas de átomos neutros (neutral íon trap) para aprisionar átomos sem carga.

Neste esquema os fótons são usados para manipular a informação contida nos átomos, dessa forma constituem um tipo de porta lógica quântica que aplica pulsos apropriados de radiação eletromagnética para que os átomos vizinhos possam interagir um com o outro como via, por exemplo, forças dipolo.

Outra classe de processamento de informação quântica é baseada na ressonância magnética nuclear (RMN). Neste caso a informação quântica é armazenada nos spins nucleares dos átomos em moléculas e as portas lógicas manipulam essa informação usando a radiação eletromagnética. Um pósitron ou elétron podem ter um spin pra cima, pra baixo e os dois ao mesmo tempo.

Os momentos magnéticos nucleares fazem um movimento natural de precessão na presença de campos magnéticos. Os estados quânticos dos núcleos podem ser manipulados irradiando os núcleos com pulsos de rádio frequência sintonizados na frequência de precessão destes.

Em um determinado composto constituído por diferentes átomos pode-se medir as ressonâncias dos núcleos de alguns átomos sem alterá-los utilizando a RMN. Ela é sensível às interações dos momentos nucleares expostos à campos elétricos e magnéticos locais, estas interações são chamadas de hiperfinas. Cada tipo de spin possui uma velocidade angular que depende do campo aplicado e da interação de troca entre eles.

Assim como na computação clássica, na computação quantica utiliza-se circuitos, porém esses circuitos são quânticos:

- **Entrada:** considera-se conjuntamente os _qubits_ de entrada, matematicamente o que é chamado de seu produto tensorial;
- **Linhas horizontais:** as linhas que aparecem não são necessariamente fios. Elas representam a evolução de um _qubit_, podendo ser apenas a passagem do tempo ou, por exemplo, o deslocamento de um fóton;
- **Sentido:** o circuito descreve a evolução do sistema quântico no tempo, da esquerda para a direita;
- **Linhas verticais:** o segmento vertical informa que o circuito atua simultaneamente nos dois _qubits_. A linha vertical representa o sincronismo, e não o envio de informação;
- **Controle:** indica que o _qubit_ representado nessa linha é um _qubit_ de controle, ou seja, caso esteja no estado | 1 ⟩ , ![{\displaystyle |1\rangle ,}](https://wikimedia.org/api/rest_v1/media/math/render/svg/3ab8dd8621da4ac3dceedaf4d812f70bb4d10ec4) a porta realiza a operação; caso esteja no estado | 0 ⟩ , ![{\displaystyle |0\rangle ,}](https://wikimedia.org/api/rest_v1/media/math/render/svg/f0d44c5fa52751e6d5277442dab35493a2a6f2f2) a porta não realiza operação alguma. Caso o _qubit_ de controle seja um estado superposto ou os 2 _qubits_ estejam emaranhados, não é possível compreender o comportamento individual do _qubit_ de controle e do _qubit_ alvo. Deve-se considerar a ação do operador unitário, que representa todo o circuito, atuando simultaneamente nos 2 _qubits_.
- **Saída:** os _qubits_ que compõem a saída do circuito podem ou não ser medidos. Como o _qubit_ inferior está sendo medido, o resultado será 0 ou 1.

Como vemos, operações lógicas ou até mesmo algoritmos podem ser descritos por um circuito quântico. Nestes circuitos podemos utilizar as portas lógicas utilizadas na computação clássica, mas podemos utilizar ainda outras que chegam a permitir, por exemplo, a construção de um possível circuito para o teletransporte de dados.

Atualmente é possível realizar qualquer operação clássica utilizando somente portas **Nand**. O mesmo ocorre em circuitos quânticos onde as portas são: Hadanard (H), Controladora (CNOT), fase (S) e ![{\displaystyle \scriptstyle {\pi }/8}](https://wikimedia.org/api/rest_v1/media/math/render/svg/c9737898d6a41f885e1a97686e64ff29d4a93509)** (T). Exemplos de portas quânticas:

- [Porta CNOT Quântica](Porta_CNOT_Quântica.md)
- [Porta NOT Quântica](Porta_NOT_Quântica.md)