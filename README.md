# Uso de LLMs (Transformers) para Apoiar Atividades de Teste de Software

## 👨‍🏫 Disciplina
Teste de Software  
Departamento de Computação  
Universidade Federal de Sergipe

## 📄 Tema da Atividade
Análise e aplicação do artigo **"ChatUniTest: a ChatGPT-based Automated Unit Test Generation Tool"**, com foco na utilização de modelos de linguagem de grande escala (LLMs) para auxiliar na geração automatizada de testes unitários.

## 👥 Integrantes
- Caio Rosberg Xavier Lima  
- Isabela de Gondra Mendonça Pereira  
- Levy dos Santos Silva  
- Virna Santos Oliveira

---

## 🗂 Seção do Artigo
**Unit test case generation**

## 📚 Link do Artigo
[ChatUniTest: A Framework for LLM-Based Test Generation (arXiv)](https://arxiv.org/abs/2305.04764)

## 📹 Vídeo Explicativo
[YouTube - Apresentação da Atividade](https://www.youtube.com/watch?v=52iYKloZDjg&authuser=2)

## 📁 Repositório da Atividade
[GitHub - Teste_de_software_LLM_2025](https://github.com/virnaoliveira/Teste_de_software_LLM_2025_Caio_Lima_Isabela_Pereira_Levy_Silva_Virna_Oliveira)

---

## 💡 Problema Abordado
A atividade foca na dificuldade comum enfrentada por desenvolvedores na criação manual de testes unitários. A proposta do artigo é o uso do **ChatUniTest**, ferramenta baseada no ChatGPT, que automatiza a geração, validação e reparo de testes unitários, reduzindo erros humanos e otimizando tempo.

## 🛠️ Solução Proposta
O ChatUniTest usa modelos **decoder-only** com arquitetura **Transformer**, capazes de entender o contexto do código-fonte e gerar testes relevantes. O processo é dividido em três etapas:
1. Geração do teste
2. Validação automática
3. Reparo (automático ou com nova interação com o modelo)

## 🤖 Modelo Utilizado
- **Nome**: ChatGPT
- **Versão**: GPT-3.5 ou GPT-4 (não especificado)
- **Acesso**: [https://chat.openai.com](https://chat.openai.com) | [API](https://platform.openai.com)
- **Arquitetura**: Decoder-only

## 📊 Dataset e Projetos Utilizados
- **Dataset**: Methods2test
- **Projetos open-source**:
  - [Commons CLI](https://github.com/apache/commons-cli)
  - [Commons CSV](https://github.com/apache/commons-csv)
  - [Gson](https://github.com/google/gson)
  - [JFreeChart](https://github.com/jfree/jfreechart)

---

## 🧪 Avaliação da Solução

### Técnica
- Comparação com EvoSuite e TestSpark
- Projetos testados: Commons-CLI, Commons-CSV, Ecommerce-microservice, Binance-connector
- **Cobertura média alcançada pelo ChatUniTest**: 59,6% (maior entre as ferramentas comparadas)

### Prática
- Feedback de 9 usuários (entre estudantes e desenvolvedores sêniores)
- 89% já usavam a ferramenta
- Sugestões incluíram suporte a múltiplas linguagens, frameworks personalizados e testes de desempenho

---

## 🧷 Exemplo de Avaliação
No projeto **Commons-CSV**:
- O ChatUniTest gerou testes com alta cobertura
- O TestSpark falhou devido a excesso de tokens no prompt
- O EvoSuite teve cobertura inferior

---

## 🚀 Aplicações no Dia a Dia
- Criação de testes para código legado
- Apoio a programadores iniciantes
- Integração com pipelines de CI/CD
- Ensino de boas práticas em testes automatizados

---

## ⚠️ Limitações da Ferramenta
- Limite de tokens nos prompts
- Dependência da qualidade do código-fonte
- Geração apenas de testes unitários
- Necessidade de revisão humana
- Suporte limitado a linguagens não populares

---

## 💡 Sugestão de Melhoria
Implementar divisão automática de prompts longos, evitando estouros de limite de tokens e permitindo o uso da ferramenta com métodos complexos sem perder informações importantes.

---

## 📌 Aplicação Prática
**Problema do StackOverflow**: ["How to write tests for legacy code and then refactor it?"](https://stackoverflow.com/questions/31276462/how-to-write-tests-for-legacy-code-and-then-refactor-it)  
A ferramenta poderia ser aplicada diretamente na geração de testes para código legado, auxiliando desenvolvedores a iniciar o processo de refatoração com segurança.

---

## 📚 Referências
- XIE, Zhuokui; CHEN, Yinghao; ZHI, Chen; DENG, Shuiguang; YIN, Jianwei. *ChatUniTest: a ChatGPT-based automated unit test generation tool*. Zhejiang University, 2023.  
  Repositório oficial: [https://github.com/ZJU-ACES-ISE/ChatUniTest](https://github.com/ZJU-ACES-ISE/ChatUniTest)

---

