# Desafio de Projeto: Gerenciamento de Instâncias AWS EC2

Este repositório foi criado para a entrega do desafio prático de computação em nuvem utilizando a AWS. O objetivo principal foi compreender o ciclo de vida, a criação e o gerenciamento de instâncias virtuais no Amazon EC2.

---

## 🎯 Objetivos do Projeto

* Configurar e implantar uma instância virtual utilizando o Amazon EC2.
* Compreender conceitos fundamentais de infraestrutura como nuvem, grupos de segurança (Security Groups), e chaves de acesso (Key Pairs).
* Documentar todo o processo de aprendizado e configuração para futuras referências.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

* **AWS (Amazon Web Services):** Provedor de computação em nuvem.
* **Amazon EC2 (Elastic Compute Cloud):** Infraestrutura como serviço (IaaS) para instâncias virtuais.
* **Git & GitHub:** Controle de versão e documentação do projeto.
* **Markdown:** Estruturação visual da documentação.

---

## 🚀 Passos Executados no Desafio

### 1. Configuração da Instância EC2
* Seleção da AMI (Amazon Machine Image) apropriada para o escopo do projeto (ex: Ubuntu Server / Amazon Linux).
* Escolha do tipo de instância (foco na elegibilidade para o nível gratuito, como `t2.micro`).

### 2. Segurança e Acesso
* Criação e download do par de chaves (`.pem` ou `.ppk`) para conexões SSH seguras.
* Configuração do **Security Group** definindo as regras de entrada (Inbound Rules) e saída (Outbound Rules), liberando as portas necessárias (ex: Porta 22 para SSH, Porta 80 para HTTP).

### 3. Inicialização e Testes
* Execução da instância e acompanhamento do status de inicialização pelo Console AWS.

---

## 🎓 Aprendizados Adquiridos

Durante as vídeo-aulas e a execução prática, foi possível consolidar conhecimentos essenciais sobre como a nuvem facilita o provisionamento de servidores de forma rápida e escalável, além da importância de configurar corretamente as regras de firewall (Security Groups) para manter a aplicação segura.

---

## 🔗 Links Úteis e Referências

* [Documentação Oficial do Amazon EC2](https://docs.aws.amazon.com/ec2/)
* [Guia de Markdown do GitHub](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
