# Desafio-de-Projeto_-Microsoft-Azure-dio-lab-introducao


# ☁️ Conceitos Fundamentais da Nuvem para a Certificação AZ-900

Este repositório contém um resumo dos conceitos básicos e introdutórios para quem está se preparando para a certificação **AZ-900: Microsoft Azure Fundamentals**. O objetivo é fornecer uma visão geral dos principais tópicos abordados no primeiro domínio da prova: **"Descrever os conceitos de nuvem"**.

---

## 🚀 Computação em Nuvem: Domínio do Objetivo

A **computação em nuvem** é a entrega de serviços de computação — incluindo servidores, armazenamento, bancos de dados, rede, software, análise e inteligência — pela Internet ("a nuvem"). Em vez de manter sua própria infraestrutura de computação, as empresas podem acessar esses serviços de um provedor de nuvem, como a Microsoft (Azure).

O domínio "Descrever os conceitos de nuvem" da certificação AZ-900 avalia sua compreensão sobre os princípios fundamentais da computação em nuvem.

Os principais **benefícios da computação em nuvem** incluem:

* **Agilidade:** Rápida implantação de recursos conforme a necessidade.
* **Elasticidade:** Capacidade de aumentar ou diminuir os recursos de forma dinâmica e automática.
* **Escalabilidade:** Capacidade de crescer em poder de processamento (vertical) ou em número de instâncias (horizontal) para atender à demanda.
* **Disponibilidade Global:** Acesso a datacenters em todo o mundo para entregar conteúdo mais rápido aos usuários.
* **Recuperação de Desastres:** Soluções simplificadas para backup e recuperação de dados.
* **Segurança:** Provedores de nuvem investem pesadamente em segurança, oferecendo recursos robustos.
* **Custo-Benefício:** Pague apenas pelo que usar (pay-as-you-go), otimizando os custos.

---

## 📊 Comparação de Modelos de Nuvem

Existem três modelos principais de implantação de nuvem, cada um com suas próprias características e casos de uso.

| Modelo | Descrição | Vantagens | Desvantagens |
| :--- | :--- | :--- | :--- |
| **Nuvem Pública** | Os recursos são de propriedade e operados por um provedor (como Microsoft, AWS, Google) e compartilhados por múltiplos clientes pela internet. | - **Sem CapEx:** Não há custos iniciais com hardware. <br> - **Alta Escalabilidade:** Recursos praticamente ilimitados. <br> - **Agilidade:** Provisionamento rápido de recursos. <br> - **Modelo OpEx:** Pague apenas pelo que consumir. | - **Menos Controle:** A infraestrutura subjacente é gerenciada pelo provedor. <br> - **Preocupações com Segurança e Conformidade:** Pode não ser ideal para dados altamente sensíveis ou setores muito regulados. |
| **Nuvem Privada** | Os recursos de computação são usados exclusivamente por uma única empresa. Pode estar no data center local (on-premises) ou ser hospedada por terceiros. | - **Maior Controle:** Controle total sobre a infraestrutura e a segurança. <br> - **Conformidade:** Mais fácil de atender a requisitos regulatórios estritos. <br> - **Segurança Aprimorada:** Isolamento completo de recursos. | - **Custos de CapEx:** Requer investimento inicial em hardware. <br> - **Responsabilidade pela Manutenção:** A própria organização é responsável pela manutenção e atualização. <br> - **Escalabilidade Limitada:** Limitada à infraestrutura que foi adquirida. |
| **Nuvem Híbrida** | Combina nuvens públicas e privadas, permitindo que dados e aplicativos sejam compartilhados entre elas de forma integrada. | - **Flexibilidade:** Permite aproveitar o melhor dos dois mundos. <br> - **Escalabilidade sob Demanda:** Use a nuvem pública para picos de carga (cloud bursting). <br> - **Conformidade e Segurança:** Mantenha dados sensíveis na nuvem privada e use a pública para o resto. | - **Complexidade:** Requer gerenciamento e integração entre os dois ambientes. <br> - **Custos de Integração:** Pode haver custos associados à conexão e manutenção da comunicação. |

---

## 💰 Comparação entre CapEx e OpEx

Um dos conceitos financeiros mais importantes na transição para a nuvem é a mudança de Despesas de Capital (CapEx) para Despesas Operacionais (OpEx).

* **CapEx (Capital Expenditure - Despesas de Capital):**
    * Refere-se ao gasto inicial com a aquisição de ativos físicos de longo prazo, como servidores, storage e equipamentos de rede.
    * É um grande investimento inicial.
    * Os custos são depreciados ao longo do tempo.
    * **Exemplo:** Comprar um servidor físico para hospedar o banco de dados da empresa.

* **OpEx (Operational Expenditure - Despesas Operacionais):**
    * Refere-se às despesas contínuas para manter o negócio funcionando, como aluguel, salários e, no caso da nuvem, o pagamento mensal pelos serviços utilizados.
    * Não há um grande investimento inicial.
    * Os custos são baseados no consumo (modelo pay-as-you-go).
    * **Exemplo:** Pagar uma fatura mensal ao Azure pelo uso de um banco de dados como serviço (SQL Database).

A computação em nuvem favorece o modelo **OpEx**, o que proporciona maior flexibilidade financeira e reduz a necessidade de grandes investimentos iniciais em infraestrutura de TI.

| Característica | CapEx (Tradicional On-Premises) | OpEx (Nuvem) |
| :--- | :--- | :--- |
| **Custo Inicial** | Alto | Baixo ou Nenhum |
| **Modelo de Custo** | Compra de ativos físicos | Pagamento por uso/assinatura |
| **Flexibilidade Financeira** | Baixa | Alta |
| **Manutenção** | Responsabilidade do proprietário | Responsabilidade do provedor de nuvem |

---

## 🔄 Computação em Nuvem - Revisão de Conceitos-Chave

Para a certificação AZ-900, é crucial solidificar os seguintes conceitos:

* **Alta Disponibilidade (High Availability - HA):** Garantir que seus aplicativos estejam operacionais e acessíveis, mesmo em caso de falhas. No Azure, isso é alcançado com recursos como Zonas de Disponibilidade e Conjuntos de Disponibilidade.
* **Escalabilidade (Scalability):** A capacidade de um sistema de lidar com uma carga de trabalho crescente. Pode ser **vertical** (aumentar a capacidade de um único recurso, como mais CPU/RAM) ou **horizontal** (adicionar mais recursos, como mais máquinas virtuais).
* **Elasticidade (Elasticity):** A capacidade de um sistema de provisionar e desprovisionar recursos de forma **automática** com base na demanda atual.
* **Tolerância a Falhas (Fault Tolerance):** A capacidade de um sistema continuar operando sem interrupção, mesmo que um ou mais de seus componentes falhem.
* **Modelo de Responsabilidade Compartilhada (Shared Responsibility Model):** Entender quais tarefas de segurança são de responsabilidade do provedor de nuvem (Microsoft) e quais são de responsabilidade do cliente. A responsabilidade do cliente aumenta de SaaS para PaaS e é maior em IaaS.

Compreender esses conceitos fundamentais fornecerá uma base sólida não apenas para a prova AZ-900, mas também para sua jornada de aprendizado contínuo no mundo da computação em nuvem com o Microsoft Azure.
