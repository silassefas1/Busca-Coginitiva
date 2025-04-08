# Configuração de Pesquisa Cognitiva com Azure

## 🧠 Objetivo
Este projeto teve como objetivo explorar os serviços de **Pesquisa Cognitiva do Azure**, configurando uma solução completa que permita realizar buscas inteligentes em documentos usando IA.

---

## 🔧 Passo a Passo da Configuração

1. **Criação da Conta de Armazenamento**
   - Criada uma conta com redundância local (LRS) na região *Brazil South*.
   - Usada para armazenar os documentos que alimentam a busca.

2. **Criação do Serviço de Busca Cognitiva**
   - Criado no portal do Azure.
   - Escolhido o plano gratuito (F0) para evitar custos.
   - Nome personalizado, com definição de região e nível de desempenho.

3. **Conexão com a Fonte de Dados**
   - Fonte configurada com os documentos (ex: PDF, Word) armazenados no Blob Storage.
   - Indexador criado para ler os arquivos e extrair o conteúdo.

4. **Aplicação de Habilidades Cognitivas**
   - Habilitado enriquecimento de IA:
     - Extração de texto.
     - Detecção de linguagem.
     - Identificação de entidades (como nomes, locais, datas).
   - Pipelines criados para executar as transformações.

5. **Criação do Índice de Busca**
   - Definidos campos pesquisáveis, ordenáveis e retornáveis.
   - Exemplo: título, conteúdo, data, entidades extraídas.

6. **Testes e Ajustes**
   - Testes realizados usando o painel de busca no Azure.
   - Verificações de resultados, ajuste de relevância e melhoria de consultas.

---

## 🔍 Insights e Possibilidades

- **Busca Semântica**: Vai além da palavra-chave, entendendo a intenção da pergunta.
- **Geração de Conhecimento**: Ótima ferramenta para transformar conteúdo não estruturado em dados pesquisáveis.
- **Acessibilidade de Dados**: Facilita encontrar informação em grandes volumes de arquivos.
- **Inteligência Contextual**: Com uso de IA, a busca se adapta ao contexto dos dados.

---

## 🛠️ Ferramentas e Tecnologias Relacionadas

- **Azure Cognitive Search**
- **Blob Storage (Azure)**
- **Form Recognizer (para extração de texto estruturado)**
- **Power BI** – para exibir insights extraídos.
- **Chatbots** – para responder perguntas com base nos dados indexados.

---

## 📚 Aprendizados

- Entendimento do processo de **indexação e enriquecimento cognitivo**.
- Compreensão das opções de **armazenamento e fontes de dados**.
- Vivência prática em configurar pipelines de IA sem escrever código.
- Importância da **curadoria de dados** para uma boa experiência de busca.
- Possibilidades de integração com aplicações de front-end e análises de dados.

---

## ✅ Conclusão

A Pesquisa Cognitiva do Azure mostrou-se uma ferramenta poderosa para criar soluções de busca inteligentes em diversos tipos de documentos, oferecendo escalabilidade, precisão e contexto sem exigir implementações complexas. Ideal para projetos de **mineração de conhecimento**, **FAQ inteligente**, **assistentes virtuais** e **sistemas de recomendação**.

