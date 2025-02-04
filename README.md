# Projeto: Laboratório de IA Generativa e Azure AI Studio

Este README documenta o processo realizado para explorar e testar os recursos de IA generativa e filtros de conteúdo no Azure AI Studio. Os seguintes laboratórios foram concluídos:

- [Explorar IA Generativa](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/12-generative-ai.html)
- [Explorar o Azure AI Studio](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/01-Explore-ai-studio.html)
- [Explorar Filtros de Conteúdo](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/06-Explore-content-filters.html)

---

## Laboratório 1: Explorar IA Generativa

### Etapas Realizadas:
1. **Acessando o Serviço OpenAI do Azure**  
   - Acessei o portal do Azure e configurei o recurso **Serviço OpenAI** chamado `TesteGenerativeAI`.  
   - Configurações utilizadas:  
     - **Região:** Leste dos EUA  
     - **Nível de Preço:** Gratuito F0  
     - **Grupo de Recursos:** IA-Labs  

2. **Gerando Conteúdo com GPT**  
   - Usei o modelo GPT para criar texto em diferentes contextos, como:  
     - Resumos automáticos.  
     - Redação de e-mails.  
     - Geração de ideias de negócios.  
   - Ajustei prompts personalizados para otimizar os resultados gerados.

3. **Resultados**  
   - Outputs gerados foram salvos no diretório `outputs/generative-ai`.  
   - Constatei a flexibilidade do modelo para atender demandas diversas.

---

## Laboratório 2: Explorar o Azure AI Studio

### Etapas Realizadas:
1. **Configuração do Azure AI Studio**  
   - Acessei o **Azure AI Studio** pelo link [https://ai.microsoft.com/studio](https://ai.microsoft.com/studio).  
   - Conectei o ambiente ao recurso `TesteGenerativeAI` previamente configurado no Azure.  

2. **Explorando Recursos do Studio**  
   - Testei ferramentas integradas, como:  
     - **Geração de Texto:** Criação de conteúdos automatizados para publicações e resumos.  
     - **Resumo de Documentos:** Análise de grandes textos com extração das informações principais.  
     - **Análise de Sentimento:** Identificação de tom emocional em mensagens.  

3. **Resultados**  
   - Outputs dos testes foram salvos no diretório `outputs/ai-studio`.  
   - Verifiquei a eficácia e usabilidade das ferramentas do Studio.

---

## Laboratório 3: Explorar Filtros de Conteúdo

### Etapas Realizadas:
1. **Habilitando Filtros de Conteúdo**  
   - Configurei filtros no **AI Studio** para garantir moderação e uso responsável.  

2. **Testando Moderação de Conteúdo**  
   - Submeti entradas sensíveis para verificar como o filtro lida com conteúdos potencialmente inadequados.  
   - Ajustei os níveis de restrição para bloquear automaticamente conteúdos ofensivos ou indesejados.  

3. **Resultados**  
   - Os filtros bloquearam eficientemente textos indesejados.  
   - Resultados foram documentados no diretório `outputs/content-filters`.  

---

## Considerações Finais

Os laboratórios realizados demonstraram:
- O poder da IA generativa para criar conteúdos automatizados e personalizados.
- A flexibilidade e utilidade do Azure AI Studio em explorar e implementar soluções práticas.
- A importância de configurar filtros de conteúdo para garantir um uso seguro e responsável da IA.

Essas ferramentas do Azure destacam-se como soluções robustas para aprimorar a produtividade e segurança em diversas aplicações corporativas.
