# 🛡️ OSINT Automated Recon Analyzer

Ferramenta automatizada de reconhecimento e coleta de informações (OSINT) desenvolvida em **Python**. O script realiza consultas em APIs públicas de infraestrutura de rede, mapeia registros DNS, extrai subdomínios via transparência de certificados e compila um relatório técnico formatado em **Markdown**.

---

## 🚀 Tecnologias e Habilidades Praticadas
- **Consumo de APIs REST** e requisições HTTP (`requests`).
- **Tratamento de exceções** robusto para falhas de rede e timeouts.
- **Manipulação e parsing de dados JSON**.
- **Desenvolvimento de CLI interativa** com feedback visual (`colorama` e `tabulate`).
- **Automação de arquivos**, gerando documentações dinâmicas em Markdown.

---

## ⚙️ Pré-requisitos e Instalação

Certifique-se de ter o Python instalado na sua máquina. Em seguida, clone o repositório e instale as dependências necessárias:

```bash
# Clone o repositório
git clone https://github.com/guiiparaiso/osint-recon-analyzer.git

# Entre na pasta do projeto
cd osint-recon-analyzer

# Instale as dependências
pip install -r requirements.txt
