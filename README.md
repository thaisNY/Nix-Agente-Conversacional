# Nix — Agente Conversacional NEOOH

O **Nix** é um assistente virtual de inteligência artificial generativa desenvolvido para a **NEOOH**, a principal operadora de mídia *Out of Home* (OOH) e *Digital Out of Home* (DOOH) no Brasil. O projeto foi criado como parte do **Bootcamp de Inteligência Artificial da SoulCode 2026**.

-----

## 🎥 Demonstração e Acesso

### Vídeos do Projeto

| Demonstração do Site |  Demonstração do Agente Conversacional |
| :---: | :---: |
| \https://www.youtube.com/watch?v=Gsc4OY0SGx8 | \https://studio.youtube.com/video/jtfM7ag1P1Q/edit |

### 🚀 Link para Deploy

Acesse o agente em execução aqui:
**[https://neooh-app-468442148173.us-central1.run.app/](https://neooh-app-468442148173.us-central1.run.app/)**

-----

## 🎯 Propósito e Objetivos

O agente tem como missão fornecer informações iniciais aos potenciais anunciantes e facilitar o primeiro contato com a empresa, tornando o processo de atendimento mais rápido e eficiente.

### Principais Funções:

  * **Informação:** Fornece dados básicos sobre a NEOOH e seus canais.
  * **Suporte:** Responde a dúvidas sobre anúncios em parques, clubes, cafeterias e shoppings.
  * **Direcionamento:** Encaminha o anunciante para o canal de atendimento adequado.
  * **Coleta de Leads:** Coleta dados do usuário para contato da equipe comercial.

-----

## 🛠️ Arquitetura Técnica

A solução foi construída utilizando uma infraestrutura robusta e escalável:

  * **Plataforma de IA:** Google Cloud (Vertex AI).
  * **Motor:** IA Generativa com lógica de prompt personalizada.
  * **Data Store:** Integração com as Diretrizes Oficiais da NEOOH para respostas precisas.
  * **Frontend:** Interface moderna construída em HTML/CSS com integração nativa do Dialogflow Messenger.
  * **Backend:** Flask (Python).

-----

## 🚀 Como Executar o Projeto

### Pré-requisitos

  * Docker instalado.
  * (Opcional) Python 3.11 se desejar rodar localmente sem containers.

### Utilizando Docker

O projeto está pronto para ser containerizado e implantado em serviços como o Google Cloud Run.

1.  **Construir a imagem:**
    ```bash
    docker build -t nix-agente .
    ```
2.  **Executar o container:**
    ```bash
    docker run -p 8080:8080 -e PORT=8080 nix-agente
    ```
    O agente estará disponível em `http://localhost:8080`.

### Instalação Local (Desenvolvimento)

1.  Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```
2.  Inicie o servidor Flask:
    ```bash
    python app.py
    ```

-----

## 👥 Equipe Multidisciplinar

O sucesso deste projeto é fruto de um esforço coletivo:

  * **Edimilza Carla de Jesus:** AI/ML Engineering.
  * **Letícia Maria Fuzer:** Consultoria Empresarial.
  * **Murillo Guedes Manalischi:** Produção Audiovisual.
  * **Thais Rodrigues:** Desenvolvedora Full Stack.
  * **Wendler Wendel Lins da Silva:** Designer Gráfico.

-----

## 📄 Licença

Este projeto está licenciado sob a **MIT License** — consulte o arquivo [LICENSE](https://www.google.com/search?q=LICENSE) para mais detalhes.



