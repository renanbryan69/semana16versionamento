# semana16versionamento


Trunk-Based Development e Divergência de Código

Primeiro, vamos entender como funciona o modelo **Trunk-Based**. Ele é uma prática de controle de versão na qual os desenvolvedores integram seus códigos com frequência em uma única ramificação principal, geralmente chamada de main ou trunk. Dessa forma, é possível evitar conflitos frequentes de mesclagem e o uso de branches muito longas.

A divergência de código ocorre quando os desenvolvedores criam branches separadas e permanecem trabalhando nelas por um período muito longo. Com o passar do tempo, essas versões começam a se distanciar do código original. Quando isso acontece, a branch pode ficar muito extensa e acumular uma grande quantidade de alterações, aumentando as chances de ocorrerem problemas durante o merge. Esse cenário é conhecido como merge hell.

Diante desse contexto, o modelo Trunk-Based pode ser uma boa solução para reduzir esse problema, pois os desenvolvedores trabalham de forma mais próxima da branch principal, realizando commits pequenos e frequentes. Isso diminui a criação de branches extensas e reduz o escopo de possíveis conflitos durante a integração do código.
