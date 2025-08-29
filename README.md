
# 🚀 TQC - QA Coders Academy - Treinamento prático de testes em uma plataforma ERP 🚀

<p align="center">
  <img src="https://img.shields.io/badge/Tecnologia-Postman-orange.svg" alt="Postman Badge" />
  <img src="https://img.shields.io/badge/Linguagem-JavaScript-yellow.svg" alt="JavaScript Badge" />
  <img src="https://img.shields.io/badge/Testes-API-blue.svg" alt="API Tests Badge" />
</p>

---

## 🎯 Sobre o Projeto

Este repositório contém uma coleção de testes de API desenvolvida no **Postman** para o sistema **ERP**. O foco principal deste projeto é a validação do endpoint de **Cadastro de Empresa**.

Os testes foram desenhados para garantir a integridade, confiabilidade e o comportamento esperado da API, cobrindo cenários de sucesso e falha.

## 📋 Funcionalidades Testadas (Endpoint: `cadastrar empresa`)

-   **Cadastro com dados válidos:** Verificação do status code `201` e da estrutura da resposta.
-   **Validação de campos obrigatórios:** Testes para dados faltantes ou incorretos (`status code 400`).
-   **Dados duplicados:** Cenários onde se tenta cadastrar uma empresa que já existe (`status code 409`).
-   **Testes de performance:** Verificação do tempo de resposta da requisição.

---

## 🛠️ Como Usar

1.  Clone este repositório para sua máquina local.
2.  Abra o Postman e importe o arquivo de coleção (`.json`) presente na raiz do projeto.
3.  (Opcional) Importe o arquivo de ambiente (`.json`) se houver.
4.  Defina o ambiente importado como o ativo.
5.  Execute a coleção e analise os resultados dos testes.

---

## 👩‍💻 Contato e Feedback

Dúvidas ou sugestões? Sinta-se à vontade para abrir uma *issue* ou entrar em contato.

**Feito com ❤️ por Bruna Pereira**
