# METODOLOGIAS ÁGEIS

## 2.1	Introdução Metodologias Ágeis

<ul>
  <li>Fundamentos</li>
  <li>Scrum</li>
  <li>Kanban</li>
  <li>Extreme Programming</li>
  <li>Modelo Spotify</li>
  <li>SAFe</li>
</ul>

## 2.2	Fundamentos da agilidade

É preciso entender a mentalidade, os valores e os princípios da Agilidade antes de entrar na prática, pois não importa qual ferramenta você irá usar, os fundamentos são os mesmos.
<ul>
<li>É o que acontece na linguagem da programação, por exemplo, em que vários frameworks do Javascript são criados para tornar o desenvolvimento mais rápido. Cada hora, teremos um framework favorito novo, mas a base da linguagem será a mesma.</li>
<li>A mentalidade ágil foi documentada pela primeira vez em 2001 e não mudou muito desde então.</li>
</ul>

Quando a gente vai desenvolver um produto, um software, estamos querendo resolver um problema. 

<i>Dependendo do tipo de problema que vamos abordar, podemos definir se faz ou não sentido seguir com a agilidade.</i>

### Problemas simples x complexos:
<ul>
  <li>Simples: quando baseado nas informações que temos no início do processo, você consegue definir uma solução.</i>
  <li>Complexo: as condições são tão variadas, que você não consegue definir uma solução no início do processo.</i>
    <ul>
      <li>Ex: para o carro autônomo funcionar, você não consegue apenas dizer qual é o destino final. Você vai precisar avaliar inúmeros fatores, como o sinal aberto ou não, estradas com buraco, pedestre passando na frente. Assim, precisará provocar o sensor para ele tomar a decisão de acordo com o ambiente.</i>
    </ul>
</ul>

### Solução Tradicional x Ágil:
<ul>
<li>3 V’s:</li>
  <ol>
    <li>Visão – o produto que você imagina que vai entregar (requisitos e dores do cliente, como solucionar essas dores);</li>
    <li>Valor – o produto que você de fato entrega para o seu cliente (o protótipo, Mínimo Produto Viável - MVP, modelo que entrega ao cliente);</li>
    <li>Validação – coloca o produto no mercado e vê como o cliente vai reagir (validar se a visão estava correta);</li>
  </ol>
<li>Transparência -> Inspeção -> Adaptação</li>
<li>Tradicional: você começa com uma visão e você a segue;</li>
  <ul>
  	<li>Você já sabe qual será a entrega ótima de valor real;</li>
	  <li>A premissa é de que você consegue prever o produto que precisa entregar para satisfazer o cliente.</li>
	  <li>É utilizado para problemas simples.</li>
  </ul>
<li>Ágil: você começa com uma visão, mas não necessariamente essa visão está correta;</li>
  <ul>
  	<li>A rota será alterada ao longo do tempo até você chegar na entrega ótima de valor real;</li>
  	<li>Quando você pega um problema complexo e tenta resolver de forma tradicional, você pode acabar errando completamente na entrega.</li>
  	<li>É utilizado para os problemas complexos.</li>
  </ul>
</ul>

<strong>Agilidade é entender que você não sabe tudo, ser rápido nas entregas e responsivo à mudança.</strong>

<ul>
  <li>Assim você evita desperdício de criar uma solução que o cliente não vai querer.</li>
  <li>O objetivo é maximizar a velocidade, maximizar a agilidade e minimizar o desperdício.</li>
  <li>Conceito de Lean: você cria o mínimo produto viável, faz o teste com o cliente, vê como ele responde e volta para fazer as modificações necessárias.</li>
</ul>

### Estratégia de entrega
<ul>
  <li>Gerar valor em curtos períodos, validar e, a partir disso, adaptar a entrega.</li>
  <li>Exemplo: skate > patinete > bicicleta > moto > carro</li>
  <li>As entregas precisam ter o potencial de resolver o problema.</li>
</ul>

<i>A metodologia ágil está mais voltada à gestão de produto.</i>

### Gestão de Produto: 
<ul>
  <li>Descoberta: definir qual é o produto, quais são as necessidades do negócio, quais são os clientes em potencial (persona, design thinking).</li>
  <li>Desenvolvimento: criar o produto.</li>
</ul>
  
### Gestão de Projeto:
<ul>
  <li>Esforço temporário para entregar produtos ou serviços através de etapas determinadas previamente e com recursos limitados;</li>
  <li>O foco será em gerenciar: escopo, tempo e custo.</li>
</ul>

## 2.3	Manifesto Ágil

Até os anos 90, a forma padrão de se entregar software era pelo modelo <strong>waterfall (cascata)</strong>. 
<ul>
  <li>Os processos nesse modelo seguem o passo a passo como degraus de uma escada. O nome “waterfall” deve-se ao fato de que se assemelha à uma cascata.</li>
  <li>Ele é equivalente ao modelo tradicional, é mais fácil de ser executado e dá uma <i>previsibilidade</i> maior de escopo, tempo e custo do projeto para as empresas.</li>
</ul>

No início dos anos 90, começaram a surgir os PCs e smart phones. 
<ul>
  <li>Com o uso pessoal dos softwares, começou a surgir a necessidade de se ter maior <i>usabilidade, experiência do usuário</i> e os problemas e softwares começaram a ficar mais complexos.</li>
  <li>Com isso, surgiram as soluções como Scrum, XP, que são as ideias leve de desenvolvimento para gerar a entrega de forma flexível e que consiga atender as mudanças de forma rápida.</li>
  <li>Foi criado em 2001 o <strong>Manifesto para Desenvolvimento Ágil de Software</strong> como boas práticas de diversos profissionais da indústria que já estavam utilizando soluções como Scrum e XP.</li>
</ul>

### Mentalidade: 
<ul>
  <li>“Estamos descobrindo maneiras melhores de desenvolver software”;</li>
  <li>Se voce entrega algo que o cliente não quer, é importante entender que o cenário é complexo e que não tem como prever todas as possibilidades;</li>
  <li>É preciso ser flexível à mudança;</li>
  <li>A visão pode ser melhorada, errar não é necessariamente ruim;</li>
  <li>Enxergar reveses como oportunidades de aprendizagem;</li>
  <li>Adotar ciclos curtos de entregas;</li>
  <li>Incentivar a colaboração entre a área de Negócios e Tecnologia;</li>
  <li>Focar na entrega de valor.</li>
</ul>

### Valores:
<ul>
  <li>Indivíduos e interações são mais importantes que os processos e ferramentas;</li>
  <li>Dificilmente uma pessoa só terá competência suficiente para resolver um problema complexo, então é importante que especialistas de diferentes áreas se comuniquem para desenvolver as soluções;</li>
  <li>Software em funcionamento é mais importante que a documentação abrangente;</li>
  <li>Colaboração com o cliente é mais importante que a negociação de contratos;</li>
  <li>Responder a mudanças é mais importante que seguir um plano.</li>
</ul>

### Princípios:

#### 1.	Projeto
<ul>
  <li>Satisfação ao cliente com software em funcionamento;</li>
	<ul>
  		<li>IKIWIS (“I Know It When I See It”): o cliente não vai saber responder se gostaria de ter uma funcionalidade sem testar o produto antes.</li>
	</ul>
  <li>Mudanças são sempre bem-vindas;</li>
  <li>Entregar sempre em ciclos curtos (poucas semanas/meses);</li>
  <li>Ritmo sustentável;</li>
	<ul>
		  <li>Não desgastar as equipes em pouco tempo, pois não vao aguentar os longos períodos de desenvolvimento.</li>
	</ul>
  <li>Progresso em função do software em funcionamento</li>
</ul>

#### 2.	Produto
<ul>
  <li>Simplicidade</li>
	<ul>
		  <li>YAGNI (“You Ain’t Gonna Need It”): utilizar o princípio de pareto 80/20 – 20% das funções dão 80% do resultado, então acelerar a entrega desses 20%.</li>
		  <li>Exemplo: na primeira versão do iPhone, o processamento era ruim e você não podia abrir duas aplicações ao mesmo tempo. Porém, para eles era importante a usabilidade e foi nisso que focaram.</li>
	</ul>
  <li>Excelência técnica</li>
	<ul>
  		<li>Você precisa fazer o mais simples pro que você precisa, e não o mais simples por comodidade.</li>
		<li>Débito técnico: quando cria uma solução que atende no momento, porém depois não atende mais. Depois, é preciso melhorar o código.</li>
	</ul>
</ul>

#### 3.	Pessoas
<ul>
  <li>Conversação face a face;</li>
  <li>Cliente como integrante da equipe;</li>
  <li>Equipes auto-organizáveis;</li>
  <li>Confiança e apoio.</li>
</ul>

#### 4.	Processo
<ul>
  <li>Refletir e ajustar;</li>
	<ul>
		  <li>O feedback rápido e aprendizado contínuo reduzem o custo de retrabalho e “overhead”.</li>
	</ul>
</ul>

## 2.4	Introdução ao Scrum

## 2.5	A equipe Scrum

## 2.6	Product Backlog

## 2.7	Definition of Done

## 2.8	Sprint Planning

## 2.9	Sprint Execution

## 2.10	Sprint Review vs Sprint Retrospective

## 2.11	Kanban

## 2.12	Extreme Programming


