# Os superpoderes de dev ou habilidades que fazem a diferença

## Desenvolver softwares vai muito além de escrever códigos

## Introdução

Na “vida de dev” em diversos  momentos alguém vai te perguntar: “Como que eu entro na área da  programação?”. É sempre uma pergunta complicada de responder, uma vez  que não existe uma “receita de bolo” pronta para isso.

Para ajudar a responder esta pergunta compilei aqui habilidades muito importantes  para todas as pessoas da área de desenvolvimento de software, reconhecer sua importância e desenvolvê-las vão facilitar muito a sua entrada e  estadia na área. Estas fazem a diferença no meu dia a dia, assim como na minha evolução profissional.

### Superpoderes

Parece um exagero, mas estas são habilidades que podem tornar  possível o impossível e que viabilizam o cenário do “Não sei, mas eu  aprendo”.

Programação é um processo contínuo de resolução de  problemas, se não entendermos o que estamos tentando fazer, escrever o  código se torna inútil, assim ter habilidades afiadas para realizar o  ciclo “entender, quebrar e resolver” é essencial para conseguirmos  enxergar o propósito e atingir o objetivo do nosso trabalho.

Listei como superpoderes de dev habilidades que viabilizam a realização deste  ciclo de resolução de problemas, que vamos fazer diariamente atuando com programação.

## 1. Comunicação

Todo processo de desenvolvimento de um software começa na comunicação,  afinal, precisamos entender qual a necessidade que precisamos atender,  logo, se entendermos errado, vamos fazer errado.

> *Se você entender errado, vai fazer errado.*

Comunicação é a sempre parte mais importante na realização de qualquer projeto, em  qualquer área, sendo também o principal motivo quando os projetos  falham. No mundo do desenvolvimento de software isso não é diferente,  podemos ter um impacto gigante por uma falha de comunicação mínima, como um site fora do ar exatamente no horário de uma grande promoção, por  uma simples confusão de horário.

Mas isso não deve ser  responsabilidade de todas as pessoas? SIM, por isso nós precisamos a  aprender a fazer nossa parte. Para a comunicação ser efetiva ela deve  ser uma via de mão dupla, devemos entender o outro e nos fazermos  entender.

É importante garantir que entendemos o que precisa ser  feito, perguntar e tirar dúvidas para garantir o entendimento e  complementar pontos que ficaram pendentes fazem toda a diferença.

Uma sugestão estude sobre **Escuta Ativa**, para aprender a escutar as outras pessoas, isso faz toda diferença,  somente assim podemos entender a importância da “atenção plena”, que irá melhorar o nosso entendimento, nos possibilitando também prestar  atenção na linguagem não verbal.

Em nossas mensagens devemos ser  claros e objetivos na organização da ideia que queremos passar, nos  preocupando também com a forma e o conteúdo. **Comunicação não violenta (CNV)** é um conceito que pode ajudar muito neste contexto, para garantir que vamos passar a mensagem correta de uma forma eficaz.

Existem diversas formas para melhorarmos nossa comunicação, mas quero falar sobre a principal: **LER**. Crie o hábito de leitura, leia muito, qualquer livro, somente assim  você vai melhorar de forma definitiva a sua capacidade interpretação e  elaboração.

## 2. Lógica de programação

Finalizamos a primeira parte, entendemos o que o software precisa fazer, agora temos que começar.

Lógica de programação é o que vai nos permitir fazer isso, em termos simples,  ela é a capacidade de descrever qualquer necessidade “do usuário” em  termos de variáveis e funções.

Um ponto importante, a lógica é  independente da linguagem de programação, através da linguagem vamos  materializar o conjunto de regras que definimos na nossa cabeça. Assim  lógica de programação é um processo mental, somente após a sua criação a trazemos para o mundo real através de uma linguagem.

Veja o seguinte exemplo, a mesma lógica será usada em diferentes linguagens:

**Necessidade**: Calcular a circunferência de um círculo dado o seu raio.

**Lógica**: A formula do cálculo é C = 2πr, coisa que dá para achar na internet, a  única variável aqui é o raio(r), uma vez que π (pi) é uma constante.  Nossa função somente deve receber o valor do raio e irá fazer o cálculo  usando a constante de π (pi).

**Implementações**

JavaScript:

```
function calculoCircunferencia (raio) {
    return 2*raio*Math.PI; 
}
```

C#:

```
using System;

namespace Projeto
{
	public class FormulasCirculo
	{
		public double CalculoCircunferencia(double raio)
		{
			return 2 * raio * Math.PI;
		}
	}
}
```

Java:

```
public class FormulasCirculo {
    public double calculoCircunferencia(double raio)
    {
		return 2 * raio * Math.PI;
    }
}
```

C:

```
#include <math.h>

double calculoCircunferencia(double raio){
    return 2*raio*M_PI;
}
```

Observe que os 4 códigos utilizam a mesma lógica.

Como aprender e exercitar a lógica de programação? Escreva muito código,  faça projetos pessoais e desafios. Mas é você que tem que fazer,  assistir o vídeo de alguém criando o projeto não vai desenvolver a sua  lógica de programação.

> *“Programar é igual ir para a academia, se ficarmos sentado olhando os outros fazendo os exercícios, não vai adiantar nada.”*

## 3. Ler a documentação

Este aqui é o passo final e o principal. Se você entendeu o que precisa  fazer, conseguiu definir em termos abstratos a lógica para a execução,  ler a documentação é o superpoder que vai te permitir implementar  qualquer coisa.

Trazendo para o exemplo do cálculo da  circunferência, como saber qual a forma de acessar a constante PI em uma linguagem de programação? Através da documentação da linguagem! Não  podemos “ter preguiça de ler”, a documentação é a forma mais rápida e  segura de obter informações.

Aqui entra também outras fontes  oficiais e confiáveis, o framework que você está usando pode não ter uma documentação completa, mas se ele estiver no github, você vai ter as *issues*, onde você consegue ver a resolução de diversos problemas. Assim sempre  que for trabalhar com alguma ferramenta é muito importante fazer um  levantamento de quais serão suas fontes de informação.

Se  acostumar a pesquisar também é muito importante, aprender a usar filtros mais complexos em ferramentas de busca e fazer pesquisas de problemas  diretamente no StackOverflow, vão facilitar muito a sua vida. Fazer as  pesquisas em inglês também ajuda, pois você terá muito mais conteúdo a  sua disposição, o que torna o famoso “inglês técnico” uma ferramenta  muito útil.

## 4. Git

Mas isso não é técnico e muito específico? Sim!

Tivemos muito trabalho para chegar aqui, não podemos perder nada do que  fizemos! O Git está aqui para garantir que não vamos perder as horas que dedicamos no desenvolvimento do nosso código.

O Git é um sistema  de controle de versão de arquivos distribuídos, hoje ele é um dos poucos softwares de uso quase unanime, não existem softwares novos neste  seguimento, somente as ferramentas mais antigas que o Git substituiu.  Aprenda bem, é algo que você vai usar, não importa onde você vá  trabalhar ou qual linguagem irá utilizar.

O Git assusta no início, por isso, crie uma conta no github, coloque todos os seus projetos de  estudo lá, que em um curto período você vai aprender e se acostumar com o uso, entendendo que o Git é o seu melhor amigo!

Créditos: https://www.doug.dev.br/2022/superpoderes-de-dev/