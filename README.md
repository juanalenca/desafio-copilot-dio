# Exploração de IA Generativa no Azure AI Foundry Portal

## Descrição do Projeto

Este repositório documenta o processo de exploração e experimentação com IA generativa utilizando o Azure AI Foundry Portal, uma plataforma da Microsoft para criar aplicações inteligentes. O objetivo foi testar as capacidades de geração de conteúdo por meio de modelos de IA, como o GPT-4, no contexto de chatbots e geração de respostas personalizadas, aplicando prompts específicos relacionados a cenários de tecnologia, engenharia e ensino, inspirados nas imagens contidas neste projeto.

### Processo Realizado

1. **Acesso ao Azure AI Foundry Portal**:
   - Acesse o portal em um navegador e faça login com uma conta válida.
   - Na página inicial, selecione "Create a project" para criar um novo projeto, que serve como um contêiner para organizar o trabalho.

2. **Criação de Recursos no Azure**:
   - No painel "Create a project", utilize um nome gerado automaticamente para o projeto ou personalize-o.
   - Selecione "Create new hub" para criar um novo hub, atribuindo um nome único, e avance para a próxima etapa.
   - Escolha uma localização específica (East US, France Central, Korea Central, West Europe, ou West US) para provisionar recursos como Azure AI Services, Azure AI Hub, Azure AI Project, Storage Account, Key Vault e Resource Group.

3. **Exploração da IA Generativa no Chat Playground**:
   - No menu lateral, acesse "Playgrounds" e selecione "Try the Chat playground" para experimentar a construção de um aplicativo de chat com modelos de IA generativa.
   - Crie um deployment associando o playground a um modelo, como o GPT-4, pesquisando e selecionando-o no menu, mantendo as configurações padrão e implantando o modelo.
   - Verifique o status do deployment em "Models and endpoints" no menu "My assets".
   - No Chat playground, selecione o modelo implantado no menu de "Deployment" e aplique as alterações para começar a interagir.

4. **Testes com Prompts**:
   - Use prompts específicos relacionados às imagens deste repositório para gerar respostas, como:
     - "I'm an engineer working in a high-tech lab with advanced equipment. Can you suggest ways to optimize the setup shown in the image?"
     - "What could be the reason a person is looking at their smartphone with a surprised expression in a tech office environment?"
     - "As a Java professor teaching a class, how can I make my lessons more engaging for students, like the professor in the image?"
     - "Based on the equipment in the lab image, what are the key technologies involved in that environment?"
     - "What three tips can you give a Java professor to make their teaching style humorous and effective, similar to the professor in the classroom image? Explain your reasoning."
     - "What are the top 10 tools or technologies an engineer in a lab like the one in the image should master? Answer with a numbered list in order of importance."
   - Analise as respostas geradas, que podem variar devido à natureza da IA generativa, e refine os prompts com base nos resultados.

5. **Fechamento**:
   - Após os testes, feche a janela do navegador.

## Estrutura do Repositório

- **inputs/**: Contém as imagens utilizadas no projeto, relacionadas a cenários de tecnologia, engenharia e ensino de Java, como um engenheiro em um laboratório, um homem interagindo com um smartphone, e um professor de Java dando aula.
- **output/**: Armazena os resultados de reconhecimento de texto extraído das imagens, como descrições ou dados gerados.

## Insights e Possibilidades Aprendidas

Durante o conteúdo, aprendi diversas lições valiosas sobre o uso de IA generativa no Azure AI Foundry Portal:

- **Capacidades da IA Generativa**: A IA generativa, como o GPT-4, pode criar respostas detalhadas e contextuais para perguntas específicas sobre tecnologia, engenharia e ensino, com base em prompts bem estruturados inspirados nas imagens.
- **Importância de Prompts Bem Definidos**: O sucesso das respostas depende de prompts específicos, iterativos e contextualizados. Por exemplo, descrever detalhes visuais das imagens (como um laboratório de alta tecnologia ou um professor engraçado) melhora a relevância e a precisão das respostas.
- **Flexibilidade do Azure AI Foundry**: A plataforma oferece uma interface amigável ("Chat playground") para experimentação rápida, permitindo associar modelos de IA e personalizar deployments, o que facilita o desenvolvimento de aplicações inteligentes para cenários técnicos e educacionais.
- **Aplicações Práticas**: As habilidades adquiridas podem ser aplicadas em projetos reais, como chatbots para suporte técnico em laboratórios, assistentes para engenheiros otimizarem equipamentos, ou ferramentas educacionais que tornem aulas de programação mais engajantes.
- **Limitações e Melhorias**: As respostas podem variar devido à natureza probabilística da IA generativa, o que exige iterações e ajustes nos prompts para refinar os resultados. Além disso, o provisionamento de recursos no Azure requer atenção a locais específicos e configuração de hubs, o que pode ser um desafio para iniciantes.

## Possibilidades Futuras

- **Desenvolvimento de Aplicações**: Expandir o uso do Azure AI Foundry para criar chatbots mais complexos, integrando modelos generativos com análises de imagens para engenharia, suporte técnico ou educação em TI.
- **Automação de Tarefas**: Utilizar IA generativa para automatizar respostas em plataformas de suporte técnico para laboratórios, otimização de equipamentos, ou planejamento de aulas de programação, personalizando experiências para engenheiros e educadores.
- **Pesquisa e Inovação**: Explorar outros modelos disponíveis no Azure AI Foundry e combinar IA generativa com visão computacional para analisar imagens de laboratórios ou salas de aula, criando soluções interdisciplinares.
- **Educação e Treinamento**: Desenvolver módulos educacionais interativos que utilizem IA generativa para ensinar programação (como Java), engenharia de sistemas ou habilidades técnicas, com base em prompts e imagens específicas.

Este projeto serve como um ponto de partida para entender e aplicar IA generativa em cenários práticos relacionados a tecnologia, engenharia e ensino, destacando tanto as oportunidades quanto os desafios dessa tecnologia emergente.
