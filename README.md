# 🏡 crewAI_consultoriaImobiliaria — Simulação de Consultoria Imobiliária com Agentes Inteligentes

## 💡 Visão Geral

Este projeto simula uma consultoria imobiliária completa utilizando agentes autônomos com base no framework **CrewAI**. O sistema é composto por múltiplos agentes especializados que colaboram entre si para oferecer ao cliente uma análise detalhada sobre imóveis disponíveis, tendências de mercado, notícias relevantes e opções de financiamento.

Cada agente possui uma função específica e utiliza ferramentas personalizadas para executar suas tarefas. O fluxo é coordenado por um **Crew**, que organiza as interações entre os agentes para gerar um relatório final completo e personalizado.

---

## 🎓 Projeto baseado em curso Udemy

Este projeto foi desenvolvido como parte dos estudos do curso [Desenvolvimento de Agentes de IA: Do Zero ao Avançado](https://www.udemy.com/course/desenvolvimento-de-agentes-de-ia-do-zero-ao-avancado/?couponCode=MT260825G1), ministrado por Rodrigo Macedo e Paulo Andrade, PhD.  
O curso aborda desde os fundamentos da inteligência artificial até a construção de agentes autônomos avançados com frameworks como CrewAI, LangChain e ADK.

---

## 🧠 Arquitetura de Agentes

### 1. 🏘️ Corretor de Imóveis
- **Descrição**: Obtém as preferências do cliente (tipo de imóvel, faixa de preço etc.) e busca imóveis compatíveis em um banco de dados CSV.
- **Objetivo**: Encontrar as melhores opções de imóveis com base nas preferências do cliente.
- **Ferramenta**: `CSVSearchTool`

### 2. 📊 Analista de Mercado Imobiliário
- **Descrição**: Analisa tendências de preços em diferentes cidades, com base em dados simulados.
- **Objetivo**: Prever valorização ou desvalorização do mercado.
- **Ferramenta**: `TendenciaPrecosImoveisTool`

### 3. 📰 Analista de Notícias Imobiliárias
- **Descrição**: Busca notícias recentes sobre o mercado imobiliário e fatores externos que impactam os preços.
- **Objetivo**: Obter informações relevantes sobre o mercado por meio de fontes externas.
- **Ferramenta**: `DuckDuckGoSearchResults`

### 4. 💰 Consultor Financeiro
- **Descrição**: Analisa a renda do cliente e sugere opções de financiamento viáveis.
- **Objetivo**: Oferecer alternativas financeiras com base nas condições do cliente.
- **Ferramenta**: Sem ferramenta externa; utiliza lógica interna.

### 5. 📝 Redator de Relatórios
- **Descrição**: Gera relatórios persuasivos e bem estruturados com base nas análises dos demais agentes.
- **Objetivo**: Criar um documento final com recomendações, tendências e opções financeiras.
- **Ferramenta**: Sem ferramenta externa; integra dados dos agentes.

---

## 🎯 Objetivo do Programa

Simular uma consultoria imobiliária inteligente e automatizada, onde agentes especializados colaboram para entregar ao cliente:

- Imóveis compatíveis com suas preferências  
- Análise de mercado e tendências de preço  
- Notícias relevantes que impactam o setor  
- Opções de financiamento personalizadas  
- Relatório final com recomendações detalhadas

---

## 🚀 Como Executar o Projeto

### ✅ Pré-requisitos
- Python 3.12+
- pip

### 📦 Instalação e Ambiente Virtual

```bash
python3.12 -m venv .crew-env
.\.crew-env\Scripts\Activate.ps1
pip install -r .\requirements.txt
```

>_Após a instalação, execute o script principal conforme definido no repositório para iniciar a simulação._

## 📚 Aprendizados
- Modelagem de agentes especializados com CrewAI
- Integração de ferramentas externas para busca e análise de dados
- Coordenação de tarefas entre agentes autônomos
- Geração de relatórios automatizados com base em múltiplas fontes

## 🔮 Próximos Passos
- Adicionar interface web com Streamlit para interação com o cliente
- Expandir o banco de dados de imóveis e notícias
- Integrar LLMs para respostas mais naturais e contextualizadas
- Criar simulações financeiras com base em dados reais

## 👩‍💻 Autora

Aline Assunção

Engenheira de Qualidade em transição para Inteligência Artificial

📫 [LinkedIn](https://www.linkedin.com/in/alineassuncaoai/)  

📬 aline.jassuncao@gmail.com

>_"Inteligência colaborativa é o futuro da tomada de decisão. E aqui, ela começa com imóveis, dados e propósito."_
