# EstacionaFácil — Sistema de Análise de Feedbacks e Indicadores

Sistema computacional para interpretação automatizada de avaliações de clientes (via Processamento de Linguagem Natural) e geração de indicadores gerenciais de satisfação para apoio à tomada de decisão.

---

## 📖 Descrição do Desafio e User Stories

O **EstacionaFácil** é um estacionamento tradicional localizado no centro da cidade que expandiu seu portfólio de serviços (vagas cobertas e avulsas, contratos mensais e semanais, planos para motos e veículos grandes, pernoite, reserva por aplicativo, lava-jato, pequenos reparos e estética automotiva). Com o aumento da concorrência e dos canais de avaliação, a gestão precisa extrair automaticamente os principais pontos de melhoria e monitorar a satisfação dos clientes por serviço.

### User Stories
* **US01:** Como gerente operacional, quero importar ou registrar feedbacks dos clientes para centralizar as avaliações em um único sistema.
* **US02:** Como sistema de NLP, quero classificar automaticamente o sentimento (positivo, neutro, negativo) e a categoria de serviço de cada comentário.
* **US03:** Como gerente operacional, quero visualizar um dashboard com indicadores de satisfação e filtrá-los por período, tipo de contrato e categoria de veículo.
* **US04:** Como gerente operacional, quero receber alertas automáticos sempre que o índice de satisfação de um serviço cair abaixo do limiar configurado.
* **US05:** Como gerente operacional, quero exportar relatórios de indicadores em PDF ou CSV para reuniões de acompanhamento.

---

## 📋 Escopo do Produto (Product Backlog)

* **RF01:** Importação ou entrada manual de comentários e feedbacks dos clientes.
* **RF02:** Classificação dos feedbacks por categoria de serviço (vaga avulsa, vaga coberta, lava-jato, estética, manobrista, app/reserva, pernoite, contrato mensal).
* **RF03:** Extração automática de palavras-chave e análise de sentimento via NLP.
* **RF04:** Painel gerencial (*dashboard*) com gráficos consolidados de satisfação.
* **RF05:** Exportação de relatórios de indicadores e feedbacks em PDF ou CSV.
* **RF06:** Emissão de alertas automáticos quando a satisfação de um serviço ficar abaixo do limiar definido.
* **RF07:** Filtragem das análises por período, tipo de contrato (avulso, semanal, mensal) e categoria de veículo (carro pequeno, carro grande, moto).
* **RNF01 - RNF06:** Manual do usuário, guia de instalação, interface web responsiva, modelagem relacional + pipeline NLP, processamento de até 1.000 avaliações em menos de 1 minuto e autenticação segura no painel.

---

## 📅 Cronograma do Projeto

```text
Semana 1 (28/08 - 04/09) ──► Levantamento de Requisitos e Documento de Visão (PDF)
Semana 2 (05/09 - 11/09) ──► Prototipação de Interfaces (HTML/CSS/JS)
Semana 3 (12/09 - 18/09) ──► Modelagem UML (Caso de Uso, Atividade, Classes, Sequência) e DER
Semana 4 (19/09 - 25/09) ──► Documentação no GitHub, Revisão e Entrega Final
