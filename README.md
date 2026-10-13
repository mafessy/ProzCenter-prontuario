PROZ CENTER — Sistema de Prontuário Eletrônico
Tecnologia, cuidado e aprendizagem conectados à realidade da área da saúde.

O PROZ CENTER é um projeto acadêmico que propõe a simulação de um sistema de prontuário eletrônico voltado à rotina de profissionais de enfermagem em uma clínica psiquiátrica. Desenvolvido com tecnologias web, o sistema reúne funcionalidades que representam atividades de organização, acompanhamento e registro de informações relacionadas ao cuidado dos pacientes. Mais do que desenvolver uma aplicação, a proposta foi compreender dificuldades presentes no cotidiano da área da saúde e explorar como a tecnologia pode contribuir para tornar determinados processos mais organizados e acessíveis.

> **Importante:** este é um projeto educacional e demonstrativo. Não deve ser utilizado para armazenar informações reais de pacientes nem para substituir sistemas profissionais de saúde.

Contexto Acadêmico:
Na Proz Educação, o aprendizado vai além do conteúdo teórico: durante a formação, desenvolvemos projetos que simulam situações do ambiente profissional, permitindo aplicar os conhecimentos adquiridos em sala de aula e compreender melhor os desafios encontrados no mercado de trabalho. Foi nesse contexto que surgiu a ideia do PROZ CENTER. A proposta nasceu a partir do mapeamento de dificuldades relatadas por alunos do curso Técnico em Enfermagem, buscando identificar situações do cotidiano profissional nas quais uma ferramenta digital poderia contribuir para a organização das atividades. A partir dessas observações, surgiu a ideia de desenvolver um sistema que simulasse recursos de apoio à rotina de técnicos de enfermagem em uma clínica psiquiátrica.
- O desenvolvimento também foi inspirado pelo período do Setembro Amarelo, campanha de conscientização sobre a prevenção do suicídio e a valorização da vida. Essa relação ajudou a direcionar o cenário escolhido para o projeto: uma clínica psiquiátrica, ambiente que exige atenção, responsabilidade e organização no acompanhamento dos pacientes. Assim, o PROZ CENTER une conhecimentos de Desenvolvimento de Sistemas e situações relacionadas à prática da Enfermagem, transformando uma proposta de aprendizagem em uma experiência de desenvolvimento voltada a desafios que podem ser encontrados no ambiente profissional.
- Sobre o vínculo institucional: embora o nome PROZ CENTER faça referência ao contexto educacional em que o projeto foi idealizado, esta é uma iniciativa acadêmica independente, desenvolvida por estudantes. O sistema não é um produto oficial, não é mantido e não possui vínculo institucional com a Proz Educação.

Funcionalidades:
O sistema reúne recursos voltados à simulação de rotinas hospitalares, incluindo:
- Cadastro e consulta de pacientes: organização das informações dos pacientes cadastrados.
- Prontuários eletrônicos: visualização e gerenciamento de registros clínicos.
- Evolução de enfermagem: registro e consulta de informações relacionadas ao acompanhamento de enfermagem.
- Gerenciamento de leitos: visualização e organização dos leitos.
- Administração de medicamentos: acompanhamento de registros e administrações pendentes.
- Painel de indicadores: apresentação de informações resumidas e indicadores do sistema.
- Acessibilidade: recursos de interface voltados a facilitar a utilização do sistema.
*As funcionalidades disponíveis dependem da versão do código presente neste repositório.*

Armazenamento de dados:
O PROZ CENTER utiliza o `localStorage` do navegador para armazenar dados localmente.
Isso significa que:
- Os dados ficam armazenados no navegador e na origem em que o sistema é executado.
- As informações podem continuar disponíveis após atualizar ou fechar a página.
- Os dados não são sincronizados automaticamente entre dispositivos ou navegadores.
- O sistema não possui, por esse mecanismo, um banco de dados centralizado ou compartilhado entre usuários.
- Limpar os dados do navegador pode apagar os registros salvos.
- O uso de outro navegador, perfil ou dispositivo não garante acesso aos mesmos dados.
  
Limitações do `localStorage`:
O `localStorage` é adequado para demonstrações e protótipos, mas não oferece, por si só, autenticação segura, controle de acesso robusto, criptografia dos registros ou cópias de segurança automáticas.
Por isso, **não insira dados pessoais reais, informações clínicas identificáveis, senhas ou outros dados sensíveis** neste projeto.
Para uma aplicação destinada ao uso real em saúde, seria necessário implementar uma arquitetura apropriada, com backend, banco de dados, autenticação, autorização, proteção dos dados, auditoria e mecanismos de backup, além de observar a legislação aplicável, incluindo a LGPD.

Tecnologias utilizadas:
- HTML5: estrutura das páginas.
- CSS3: estilos, layout e adaptação da interface.
- JavaScript: funcionalidades, interações e manipulação dos dados.
- Web Storage API (`localStorage`): persistência local das informações no navegador.

Como executar:
Como o projeto utiliza tecnologias web, é possível executá-lo em um navegador moderno. Você pode acessar o site (https://proz-center.htmly.com.br/) ou então:
1. Clone ou baixe este repositório.
2. Mantenha os arquivos e recursos do projeto na estrutura de pastas esperada.
3. Abra o arquivo `index.html` em um navegador ou utilize um servidor local, como a extensão Live Server do Visual Studio Code.
4. Utilize a interface para explorar as funcionalidades disponíveis.
> **Observação:** algumas funcionalidades podem depender de recursos externos ou do contexto em que a página é executada. Se houver problemas ao abrir o HTML diretamente, utilize um servidor local.

Hospedagem:
O projeto está publicado em serviços de hospedagem de páginas estáticas (HTMLy), com os arquivos e recursos necessários disponibilizados corretamente.
Como o armazenamento utiliza `localStorage`, hospedar o sistema na internet não transforma os dados em informações compartilhadas entre os usuários. Cada navegador mantém seu próprio armazenamento local, separado dos demais.
A compatibilidade com plataformas específicas de hospedagem depende das permissões e restrições aplicadas ao HTML, CSS e JavaScript.

Privacidade e segurança:
O PROZ CENTER foi desenvolvido para fins de estudo e demonstração de conceitos de desenvolvimento web aplicados a rotinas de saúde.
- Não utilize informações reais de pacientes.
- Não considere o `localStorage` um banco de dados seguro.
- Não compartilhe dados sensíveis por meio da aplicação.
- Para uso em produção, implemente controles de segurança e uma arquitetura adequada ao tratamento de informações de saúde.

Status do projeto:
Projeto acadêmico já concluído e apresentado. No entanto, ainda está sujeito a ajustes, correções e melhorias de interface, usabilidade, acessibilidade e organização do código.

Contribuições:
Sugestões, relatos de problemas e propostas de melhoria são bem-vindos. Ao contribuir, descreva a alteração sugerida e, quando possível, inclua os passos necessários para reproduzir o problema.
