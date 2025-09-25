<p align="center"><img src="./files/contabilizei.svg" width="400" alt="Clube Vestcasa Logo"></p>

<br>

<p align="center">Case Contabilizei – EI DISCOVERY: Democratizando Dados com IA - <b>INFO-4-ALL FIAP 2025</b></p>

## 📌 Menu

1. [Declaração de Problema &  Mapa de Empatia – Usuário da Plataforma](./MAPA_EMPATIA_DECLARACAO_DE_PROBLEMA.md)

1. [Objetivo da Solução](#1-objetivo-da-solução)

1. [Avaliação de Mercado](#2-avaliação-de-mercado)

1. [Atributos Técnicos e Funcionais](#3-atributos-técnicos-e-funcionais)

1. [Modelo de Licenciamento e Custo](#4-modelo-de-licenciamento-e-custo)
1. [Buy vs. Build](#5-buy-vs-build)

1. [Open Source vs. Proprietário](#6-open-source-vs-proprietário)

1. [Casos de Uso e Referências](#7-casos-de-uso-e-referências)



## 1. Objetivo da Solução

**Qual problema a plataforma deve resolver?**  
Hoje as áreas de negócio dependem do time técnico para consultar, cruzar e visualizar dados. Isso gera **lentidão e gargalos**.

**O que a plataforma deve resolver:**

- Dar **autonomia** para qualquer usuário consultar, visualizar e entender dados em português natural.
- Reduzir a dependência do time de TI e acelerar decisões.

**Categoria:**  
Não é só automação de processos, nem só criação de apps → é uma **plataforma de análise de dados com IA** (_self-service BI + NLP + explicações_).

- **Self-service BI** → o usuário monta relatórios e dashboards sozinho, tipo Power BI/Tableau, mas sem precisar dominar SQL.
- **NLP (Processamento de Linguagem Natural)** → em vez de query técnica, o usuário pergunta em português:  
  _“Qual foi o lucro por região no último trimestre?”_ → a IA traduz em SQL.
- **Explicações automáticas** → além do gráfico, a IA escreve insights:  
  _“O lucro caiu no Sul por aumento de custos logísticos em abril.”_

👉 **Resultado esperado:** democratização dos dados → qualquer pessoa acessa, entende e decide, sem travar o time técnico.

## 2. Avaliação de Mercado

- Utilizar **Quadrante Mágico do Gartner** ou **Forrester Wave** para mapear líderes, desafiantes e nichos.
- Verificar presença em **G2, Capterra** e relatórios de analistas.
- Benchmark de players relevantes: Power BI, Tableau, Qlik, Looker, Jestor, Budibase, Appsmith, n8n.

## 3. Atributos Técnicos e Funcionais

- Facilidade de uso (**UX/UI**)
- Integração com APIs e conectores
- Escalabilidade e performance
- Segurança e compliance (**LGPD, SOC2**)
- Suporte a **workflows complexos**
- Colaboração em time e versionamento

## 4. Modelo de Licenciamento e Custo

- Preço por usuário, por app ou por volume de uso
- Comparação com alternativas open source
- Avaliar custo de suporte: Free ≠ Sustentável

## 5. Buy vs. Build

O conceito de **Buy or Build** refere-se à decisão estratégica que uma organização precisa tomar ao avaliar se deve **comprar** uma solução pronta ou **desenvolver internamente** com seus próprios recursos.

### 5.1 Comprar (Buy)

**Vantagens**

- Implementação mais rápida
- Menor risco técnico
- Suporte e atualizações garantidos
- Permite foco no core business

**Desvantagens**

- Menor flexibilidade para personalizações
- Dependência de terceiros (vendor lock-in)
- Custos recorrentes (licenciamento, manutenção, suporte)

### 5.2 Construir (Build)

**Vantagens**

- Total controle sobre funcionalidades e evolução
- Personalização completa, adaptada às necessidades específicas
- Pode gerar vantagem competitiva exclusiva

**Desvantagens**

- Maior tempo de desenvolvimento
- Riscos técnicos e de projeto
- Necessidade de equipe altamente qualificada
- Custos iniciais mais elevados

### 5.3 Critérios de Decisão

A escolha entre comprar ou construir depende de fatores como:

- Urgência da necessidade
- Complexidade da solução
- Recursos disponíveis (tempo, equipe, orçamento)
- Estratégia de longo prazo
- Nível de diferenciação desejado

## 6. Open Source vs. Proprietário

- Open Source → Budibase, Appsmith, n8n
- Proprietário → Power BI, Tableau, Jestor

| Critério / Plataforma | **Open Source** (Budibase, Appsmith, n8n) | **Proprietário** (Power BI, Tableau, Jestor) |
|---|---|---|
| **Comunidade ativa** | Forte em GitHub, fóruns e Slack. Contribuições abertas e rápidas, mas dependem do engajamento da comunidade. | Grande base de usuários, ecossistema de consultorias e treinamentos. Comunidade mais centrada no fornecedor. |
| **Documentação** | Aberta, colaborativa e acessível. Pode ter lacunas em recursos avançados (segurança, escalabilidade). | Documentação oficial robusta, guias completos, treinamentos certificados e suporte técnico dedicado. |
| **Customização** | Alto grau: código aberto, APIs e extensões. Flexibilidade para criar módulos sob medida. | Customizações possíveis, mas limitadas ao que o vendor permite. Risco de **vendor lock-in**. |
| **Segurança e Compliance** | Responsabilidade do usuário (deploy, patches, acessos). Oferece RBAC e SSO, mas maturidade varia. | Certificações (SOC, ISO, GDPR, LGPD), updates automáticos e auditorias frequentes. SLA de segurança incluso. |

## Observações por Plataforma

### 🟢 **Open Source**
- **Budibase**  
  - Licença GPL v3, permite auto-hospedagem.  
  - Oferece RBAC, SSO gratuito e integrações com diversas fontes.  
  - Recursos avançados podem exigir planos pagos.  

- **Appsmith**  
  - Forte para criar UIs customizadas e conectar APIs/BDs.  
  - Usado como alternativa leve a BI, mas precisa de customizações.  
  - Templates e módulos mantidos pela comunidade.  

- **n8n**  
  - Focado em automação e orquestração de fluxos.  
  - Open source com modelo “fair code”.  
  - Ideal para integrar múltiplos sistemas sem depender de TI.  

### 🔵 **Proprietário**
- **Power BI**  
  - Forte integração com Microsoft (Excel, Azure, Teams).  
  - Recurso de Q&A (perguntas em linguagem natural).  
  - Licenciamento competitivo, mas dependente do ecossistema MS.  

- **Tableau**  
  - Visualizações avançadas e “Ask Data” (NLP).  
  - Muito usado em empresas globais com maturidade em BI.  
  - Custo mais elevado, mas alta confiabilidade.  

- **Jestor**  
  - Plataforma para apps internos + BI leve.  
  - Serviço gerenciado com suporte contínuo.  
  - Bom para empresas que buscam simplicidade, mas menos robusto que Power BI/Tableau.  


## 7. Casos de Uso e Referências

- Estudos de caso em empresas data-driven
- Benchmarks de setores (contabilidade, financeiro, RH, vendas)
- Depoimentos de empresas que migraram para **self-service BI + IA**
