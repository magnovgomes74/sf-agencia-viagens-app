<div align="center">
  <img src="./docs/logooAgencia.png" alt="Logo Agência Magno Viagens" width="180" />
  <h1>✈️ Agência Magno Viagens — Salesforce App</h1>
  <p>Aplicação desenvolvida na plataforma Salesforce aplicando arquitetura Salesforce DX, automações e desenvolvimento Back-end/Front-end.</p>
</div>

---

## 📋 Sobre o Projeto

O **Agência Magno Viagens** é um projeto prático desenvolvido para gerenciar operações de turismo, pacotes de viagens, clientes e oportunidades comerciais dentro do ecossistema **Salesforce CRM**.

O repositório segue a estrutura padrão **Salesforce DX (SFDX)**, permitindo o controle de versão dos metadados, deploy automatizado e organização modular do código-fonte.

---

## 🛠️ Tecnologias e Recursos Utilizados

* **Plataforma:** Salesforce CRM (Lightning Experience)
* **Linguagem Back-end:** Apex (POO, Controllers MVC, Padrão DTO/Wrapper, Triggers e Batch Apex)
* **Consultas e Dados:** SOQL e DML
* **Automação Declarativa:** Salesforce Flows e Invocable Methods
* **Ferramentas de Desenvolvimento:** Salesforce CLI (`sf`), Visual Studio Code e Git/GitHub

---

## 📂 Estrutura do Projeto

```text
agencia-magnovgomes-viagens/
├── config/                  # Configurações de Scratch Orgs
├── docs/                    # Documentação, logo e certificados do projeto
├── force-app/main/default/  # Metadados principais (Classes Apex, Objetos, Triggers, Flows, LWC)
├── manifest/                # Arquivos package.xml para deploy e retrieve
├── scripts/                 # Scripts Apex anônimos e SOQL para testes
└── sfdx-project.json        # Configuração raiz do projeto Salesforce DX
