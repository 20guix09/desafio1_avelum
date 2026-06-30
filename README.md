# desafio1_avelum

# 🐾 Atendente Automático de E-mail - Petshop Patas Felizes

Este projeto foi desenvolvido como o **Desafio da Semana** na **Avelum Labs**. O objetivo principal é construir um sistema de atendimento automatizado para um petshop fictício, integrando a inteligência artificial à nossa caixa de entrada de e-mails.

O projeto utiliza o **Claude Code** conectado ao **Gmail** através do protocolo **MCP (Model Context Protocol)**. A IA atua como um assistente de suporte cortês, respondendo às dúvidas dos clientes de forma autônoma, mas sob comando manual, garantindo que o controle permaneça sempre com o utilizador.

## 🧠 Como Funciona

1. O cliente envia um e-mail para o Gmail do petshop com dúvidas sobre serviços, horários ou políticas.
2. Através do Claude Code no terminal, executamos o comando: `"Responda todos os e-mails."`
3. A IA lê cada e-mail pendente, analisa a base de conhecimento modular (arquivos `.md`) e responde ao cliente de forma personalizada e extremamente educada.

## 🗂️ Estrutura da Base de Conhecimento (Regras)

O "cérebro" do atendimento foi modularizado em arquivos Markdown dentro da pasta `regras/` para facilitar a manutenção e leitura pela IA:

* `regras/1_tom_de_voz.md`: Diretrizes para garantir um atendimento cortês, acolhedor e empático.
* `regras/2_funcionamento.md`: Informações detalhadas sobre os horários de atendimento em dias úteis e sábados.
* `regras/3_servicos.md`: Catálogo de serviços oferecidos, especificando o atendimento a cães de todos os portes.
* `regras/4_politicas.md`: Regras de agendamento, métodos de pagamento aceitos e políticas de cancelamento.

## 🛠️ Tecnologias Utilizadas

* **Claude Code** (Anthropic)
* **Model Context Protocol (MCP)**
* **Gmail API** (Google Cloud Console)
* **Markdown** (Documentação das regras)
