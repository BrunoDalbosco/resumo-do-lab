# resumo-do-lab

# aula 1 - 
A computação em nuvem é o fornecimento de serviços de computação — como servidores, armazenamento, bancos de dados, redes, software, entre outros — por meio da internet. Esse modelo permite maior agilidade na inovação, flexibilidade no uso dos recursos e significativa economia de escala, pois os usuários pagam apenas pelos serviços que utilizam, sem a necessidade de grandes investimentos iniciais.

Existem três principais modelos de nuvem: pública, privada e híbrida. A nuvem pública é gerenciada por provedores como a Microsoft, e seus recursos são compartilhados entre diversos usuários e organizações. Ela é acessada pela internet de forma segura e oferece escalabilidade com baixo custo inicial. Já a nuvem privada é criada e mantida internamente por uma única organização, geralmente dentro de seu próprio datacenter. Esse modelo proporciona controle total sobre segurança e gerenciamento, mas exige maior investimento e responsabilidade de manutenção. A nuvem híbrida combina os dois modelos anteriores, permitindo que aplicações sejam executadas no ambiente mais apropriado conforme necessidade. Essa abordagem oferece a maior flexibilidade, possibilitando controle sobre segurança, conformidade e requisitos legais.

Em relação aos custos, é importante entender a diferença entre CapEx (Capital Expenditure) e OpEx (Operational Expenditure). O CapEx envolve gastos com infraestrutura física, como servidores e datacenters, que exigem um investimento inicial elevado e têm seu valor depreciado com o tempo. Já o OpEx está relacionado a despesas operacionais, com pagamento feito conforme o uso dos recursos, de forma sob demanda, o que é característico da computação em nuvem.

A computação em nuvem opera com base em um modelo de consumo, ou seja, os usuários pagam somente pelos recursos que realmente utilizam. Isso permite melhor previsão de custos, cobrança baseada em uso real e acesso a preços detalhados por recurso ou serviço.

Assim, ao escolher entre os modelos de nuvem e os tipos de despesa, as organizações podem alinhar suas estratégias de TI às suas necessidades financeiras e operacionais, aproveitando os benefícios da escalabilidade, controle e eficiência que a computação em nuvem oferece.

# aula 2 - 
A computação em nuvem oferece uma série de benefícios que tornam os serviços mais eficientes, escaláveis e seguros. No contexto do Microsoft Azure, esses benefícios são fundamentais para garantir o bom funcionamento de aplicações e infraestrutura, especialmente em ambientes corporativos.

Um dos principais pontos é a alta disponibilidade, que assegura que os serviços estejam sempre acessíveis, mesmo diante de falhas ou interrupções. O Azure oferece garantias de tempo de atividade por meio dos chamados SLAs (Acordos de Nível de Serviço), reforçando seu compromisso com a continuidade dos negócios.

Outro benefício importante é a escalabilidade, que permite aumentar ou reduzir os recursos de forma flexível conforme a demanda. Isso pode ser feito de forma vertical, com o acréscimo de CPU e memória, ou horizontal, com a adição de mais instâncias. Como o modelo de nuvem é baseado em consumo, o usuário paga apenas pelo que realmente utiliza, o que torna o uso de recursos mais econômico e eficiente.

A elasticidade complementa a escalabilidade ao permitir ajustes automáticos na infraestrutura, especialmente em momentos de picos de uso. Isso garante que os recursos sejam ampliados ou reduzidos conforme necessário, otimizando a performance e o custo operacional.

A confiabilidade é garantida por um design descentralizado, que distribui os recursos em diversas regiões. Isso proporciona resiliência diante de falhas locais, já que os serviços podem continuar funcionando em outras áreas do mundo.

A previsibilidade também é um destaque, tanto em relação ao desempenho quanto aos custos. Com o suporte do Azure Well-Architected Framework, é possível avançar com mais confiança em projetos e planejamentos.

Em termos de segurança, a nuvem oferece ferramentas avançadas que podem ser configuradas de acordo com a necessidade do cliente. A depender do modelo adotado (IaaS, PaaS ou SaaS), o nível de controle pode variar, permitindo ao usuário gerenciar desde o sistema operacional até as atualizações automáticas de software.

A governança na nuvem permite o monitoramento contínuo de conformidade com políticas internas e regulatórias. Além disso, possibilita a aplicação automática de patches e atualizações, contribuindo para um ambiente mais seguro e bem controlado.

Por fim, a gerenciabilidade facilita o controle dos recursos por meio de interfaces como portais web, linhas de comando, APIs e PowerShell. Com isso, é possível automatizar tarefas, como a implantação de recursos com base em modelos pré-configurados e a escalabilidade conforme a demanda.

# aula 3 - 
A computação em nuvem revolucionou a forma como empresas consomem tecnologia, oferecendo serviços sob demanda com escalabilidade, flexibilidade e economia. No Microsoft Azure, esses serviços são organizados principalmente em três modelos: IaaS, PaaS e SaaS.

O modelo IaaS (Infraestrutura como Serviço) oferece ao cliente o controle total da infraestrutura, como servidores, máquinas virtuais, armazenamento e redes. Esse modelo é ideal para empresas que precisam migrar seus data centers para a nuvem, executar ambientes de teste e desenvolvimento, ou manter aplicações que exigem uma configuração personalizada.

Já o PaaS (Plataforma como Serviço) oferece um ambiente pronto para o desenvolvimento e implantação de aplicações. Ele permite que os desenvolvedores foquem exclusivamente na lógica de negócio, sem se preocupar com a manutenção da infraestrutura. É uma ótima opção para empresas que desejam acelerar a criação de softwares, usando ferramentas integradas e recursos de automação.

Por fim, o SaaS (Software como Serviço) disponibiliza softwares prontos para uso, acessíveis diretamente pela internet. Os exemplos mais comuns são ferramentas como e-mail, calendário e pacotes de produtividade, como o Microsoft 365. Nesse modelo, o provedor de nuvem é totalmente responsável pela manutenção, atualizações e segurança do software.

Esses modelos funcionam com base em um modelo de responsabilidade compartilhada, no qual o nível de controle e responsabilidade varia conforme o tipo de serviço escolhido. No IaaS, a maior parte da responsabilidade está com o cliente. No PaaS, há um equilíbrio. Já no SaaS, o provedor assume quase todas as responsabilidades.

A escolha entre IaaS, PaaS e SaaS depende das necessidades da empresa, do nível de controle desejado e da complexidade da solução. Com a nuvem, é possível escalar recursos conforme a demanda, garantir alta disponibilidade e segurança, além de reduzir custos com infraestrutura física.

# aula 4 -
O módulo apresenta os fundamentos da arquitetura e dos serviços do Microsoft Azure, destacando como a infraestrutura da nuvem é organizada e como os recursos são gerenciados dentro da plataforma.

A estrutura física do Azure é formada por regiões, que são áreas geográficas amplas que hospedam datacenters próximos entre si, otimizando o desempenho e garantindo a conformidade legal de dados. No total, o Azure oferece mais de 60 regiões espalhadas por mais de 140 países.

Dentro dessas regiões, existem as zonas de disponibilidade, que são locais fisicamente distintos com fontes independentes de energia, resfriamento e rede. Elas são projetadas para garantir alta disponibilidade dos serviços, mesmo diante de falhas locais. Para ampliar ainda mais a segurança e a recuperação de desastres, o Azure implementa os pares de regiões, que são regiões emparelhadas estrategicamente, mantendo uma distância mínima de 300 milhas entre si. Essas regiões emparelhadas são atualizadas de forma sequencial para reduzir o impacto em caso de falhas.

Há também as regiões soberanas, criadas especialmente para atender às necessidades de agências governamentais e organizações que exigem alto nível de segurança e conformidade. Um exemplo é o Azure Governamental dos Estados Unidos, que é fisicamente isolado da nuvem pública e acessível somente a usuários autorizados.

Em termos de gerenciamento de recursos, o Azure trabalha com recursos e grupos de recursos. Recursos são os elementos que compõem as soluções na nuvem, como máquinas virtuais, bancos de dados, redes e serviços de armazenamento. Já os grupos de recursos funcionam como contêineres lógicos que reúnem e organizam esses recursos. Um recurso pode estar apenas em um grupo de cada vez, mas pode ser movido para outro grupo ou usado por aplicativos que acessam múltiplos grupos.

O acesso aos serviços do Azure é feito por meio de uma conta do Azure, que pode ser padrão, para estudantes ou gratuita. Essa conta está associada a uma ou mais assinaturas, que representam a estrutura de cobrança e gerenciamento. Cada assinatura fornece acesso autorizado aos serviços e pode ser usada para segmentar ambientes diferentes (como produção, desenvolvimento ou testes).

Para facilitar o gerenciamento de múltiplas assinaturas, o Azure também disponibiliza os grupos de gerenciamento, que permitem aplicar políticas e controles de forma centralizada.

# aula 5 - 
O Microsoft Azure oferece uma ampla gama de serviços de computação em nuvem que proporcionam flexibilidade, escalabilidade e controle sobre os recursos. Dentre os principais serviços estão as Máquinas Virtuais (VMs), que permitem simular um computador físico com total controle sobre o sistema operacional e os aplicativos instalados. As VMs suportam diferentes sistemas operacionais, como Windows e Linux, e possibilitam escalabilidade e alta disponibilidade por meio de conjuntos de dimensionamento e conjuntos de disponibilidade, garantindo o funcionamento contínuo mesmo em caso de falhas.

Outro serviço importante é a Área de Trabalho Virtual do Azure, que oferece desktops e aplicativos virtualizados acessíveis de qualquer lugar, através de um navegador ou aplicativo. Isso facilita a colaboração e o trabalho remoto, permitindo múltiplos usuários simultâneos, com a segurança e a praticidade da nuvem.

Para aplicações modernas e baseadas em microsserviços, o Azure disponibiliza recursos como contêineres, que são ambientes leves e isolados para execução de aplicativos, e que podem ser orquestrados com o Azure Kubernetes Service (AKS). Além disso, o Azure suporta a execução de código sob demanda através das Azure Functions, que seguem o modelo serverless, eliminando a necessidade de gerenciar servidores.

A plataforma de aplicativos do Azure oferece uma solução gerenciada para desenvolver, hospedar e escalar aplicativos web e APIs. Ela é compatível com diversas linguagens de programação como .NET, Java, Node.js, Python e PHP. Essa plataforma atende requisitos empresariais de conformidade, segurança e desempenho, com recursos de automação e integração contínua.

No campo das redes, o Azure possibilita a criação de Redes Virtuais (VNets), que conectam recursos do Azure entre si e com redes locais. As VNets podem ser configuradas com pontos de extremidade públicos (para acesso pela internet) ou privados (para comunicação interna). Dentro das redes, é possível criar sub-redes e realizar emparelhamentos entre diferentes VNets, facilitando a comunicação entre recursos de maneira segura.

Para conexão entre a nuvem e o ambiente local, o Azure oferece Gateways de VPN, que estabelecem túneis criptografados através da internet pública. Já o ExpressRoute proporciona uma conexão privada e de alta velocidade entre a infraestrutura local e o Azure, ideal para cargas de trabalho que exigem baixa latência e maior segurança.

Por fim, o DNS do Azure permite gerenciar nomes de domínio com alta confiabilidade, tanto para domínios públicos quanto privados. Ele oferece integração com os recursos da plataforma, suporte a domínios personalizados, controle de acesso baseado em função e registro de logs para auditoria e diagnóstico.
