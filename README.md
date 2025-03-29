# ⛓️ MyChain Wallet 💰📱💻

[![React][react-shield]][react-url]
[![Meteor][meteor-shield]][meteor-url]
[![Version][version-shield]][version-url]
[![Status][status-shield]][status-url]
[![License: Proprietary][license-shield]][license-url]
[![Maintainer: Replika AI Solutions][maintainer-shield]][maintainer-url]
[![Last Commit][last-commit-shield]][last-commit-url]

**O Ecossistema Completo para seus Tokens MyChain (MCH)!** ✨

Bem-vindo à **MyChain Wallet**, a carteira digital oficial e integrada projetada especificamente para interagir com a blockchain modular **MyChain**. Desenvolvida pela **Replika AI Solutions**, esta aplicação (Web, Mobile e Desktop) é a sua porta de entrada para gerenciar, transacionar, fazer stake e explorar todo o potencial dos tokens MCH.

**Atenção:** ⚠️ Este projeto encontra-se em fase **MVP (Minimum Viable Product) - v0.1** e está em **desenvolvimento ativo e experimental**. Funcionalidades podem mudar e bugs podem estar presentes. Use com cautela.

---

## 🌟 Sobre o Projeto

A MyChain Wallet nasceu da necessidade de uma solução robusta, segura e intuitiva para os usuários do ecossistema MyChain. Construída com as tecnologias modernas **React JS** e **Meteor JS**, a carteira oferece uma experiência fluida e reativa em múltiplas plataformas.

**Objetivos Principais:**

*   **💼 Gerenciamento Completo:** Visualize saldos, crie múltiplas carteiras (Principal, Poupança, Stake) e acompanhe seu portfólio MCH.
*   **💸 Transações Simplificadas:** Envie e receba tokens MCH de forma rápida e segura com endereços e QR Codes.
*   **📈 Staking & Recompensas:** Participe do ecossistema fazendo stake de seus tokens MCH em diferentes períodos e ganhe recompensas (APY variável).
*   **💧 Pools de Liquidez & Mineração:** Aloque seus tokens em Pools de Liquidez ou participe de Pools de Mineração diretamente pela carteira.
*   **🛒 Compra de Tokens:** Adquira tokens MCH diretamente na aplicação utilizando métodos de pagamento como PIX e Cartão de Crédito (funcionalidade em desenvolvimento/MVP).
*   **📊 Dados On-Chain:** Acesse estatísticas de mercado, métricas de supply, dados da rede e histórico detalhado de transações.
*   **🔐 Segurança:** Implementação de processos de verificação (email, senha) e foco na segurança das suas chaves e fundos (em evolução).
*   **🎨 Experiência do Usuário:** Interface limpa, moderna (com Tema Escuro) e focada na facilidade de uso.

---

## 🚀 Funcionalidades Principais (Baseadas nas Telas - v0.1 MVP)

Esta versão MVP da MyChain Wallet já demonstra um conjunto rico de funcionalidades essenciais:

### 🔑 Autenticação e Segurança
*   **Login:** Tela de acesso com campos para email/usuário e senha. Opção "Esqueceu a senha?".
*   **Cadastro (Criar Conta):** Formulário para registro de novos usuários (Nome Completo, Email, Senha, Confirmação de Senha). Link para Termos de Serviço e Política de Privacidade.
*   **Recuperação de Senha:** Fluxo para solicitar link de redefinição via email. Confirmação de envio do link.
*   **Verificação de Email:** Etapa de verificação com código enviado para o email do usuário (input de 6 dígitos, botão "Verificar", opção "Reenviar código"). Tela de sucesso na verificação.
*   **Alteração de Senha (Fluxo Completo):**
    *   Verificação de identidade via código enviado por email (requer senha atual).
    *   Input da Nova Senha e Confirmação.
    *   Mensagem de sucesso "Senha Alterada!".

### 🏠 Tela Principal (Home/Dashboard Inicial)
*   **Visão Geral do Saldo:** Exibe o saldo total em MCH e seu equivalente em BRL. Ícone para ocultar/mostrar saldo.
*   **Ações Rápidas:** Botões proeminentes para "Enviar", "Receber" e "Comprar" tokens.
*   **Gráfico de Preço (MCH/BRL):** Visualização da performance do token com seletores de período (30d, 60d, 90d, 365d, total).
*   **Estatísticas de Preço:** Indicadores chave como Máxima/Mínima (24h, Mensal, Anual) e Variação percentual correspondente.
*   **Navegação Inferior:** Acesso rápido às seções: Home, Dashboard, Carteiras, Stake, Settings.

### 📊 Dashboard Detalhado
*   **Métricas do Token:** Preço atual, Volume 24h, Capitalização de Mercado, Fornecimento Circulante/Total, Inflação Anual, Queima de Tokens, Valor Total Bloqueado (TVL), Liquidez DEX, Volume DEX 24h, APR de Staking.
*   **Visão Geral da Rede:** Mineradores Ativos, Blocos Minerados, Transações/Dia, Tempo de Bloco, Carteiras Ativas, Nós da Rede, Taxa de Hash, Dificuldade.
*   **Atividade da Carteira (Exemplo):** Saldo Disponível, Saldo Médio, Recompensas Ganhas, Transações Enviadas/Recebidas, Taxas Pagas, Novas Carteiras (Hoje).
*   **Dados Técnicos:** Altura do Bloco, Último Bloco, Gas Médio, Transações Pendentes, Próxima Redução pela Metade (Halving), Segurança da Carteira, Versão do App, Link para Verificação/Documentação.
*   **Estatísticas de Mercado (Alternativo):** Preço MCH, Variação 24h, Holders, Blocos 24h.
*   **Métricas de Supply:** Supply Máximo, Em Circulação, Total Staked, Em Liquidez.
*   **Queima e Distribuição:** Queimados 24h, Distribuídos 24h, Mineradores, Hashrate.

### 💼 Gerenciamento de Carteiras
*   **Minhas Carteiras:** Lista as carteiras do usuário (Principal, Poupança, Stake) com seus respectivos saldos e endereços (parciais). Botão para adicionar nova carteira.
*   **Criar Nova Carteira:** Modal para definir o Nome da Carteira e selecionar o Tipo (Principal, Poupança, Staking).
*   **Detalhes da Carteira:** Visualização individual de cada carteira com Saldo (MCH e BRL), Endereço completo e botão "Copiar".
    *   **Carteira Principal:** Botões "Enviar" e "Receber".
    *   **Carteira de Poupança:** Botão "Operações" (Depositar/Resgatar).
    *   **Carteira de Stake:** Botão "Operações de Stake".

### 💸 Enviar e Receber Tokens
*   **Receber Tokens:** Exibe o QR Code da Carteira Principal, endereço completo, botões "Copiar" e "Compartilhar". Aviso sobre enviar apenas tokens MCH.
*   **Enviar Tokens:** Formulário para inserir Quantidade (MCH) e Endereço do Destinatário. Exibe Taxa de Rede, Taxa de Queima e Total a ser debitado. Botão "Continuar". Aviso de "Saldo insuficiente".

### 🛒 Compra de Tokens (Fluxo MVP)
*   **Iniciar Compra:** Selecionar a quantidade de MCH desejada.
*   **Método de Pagamento:** Opções PIX (Pagamento instantâneo) e Cartão de Crédito (Visa, Mastercard, Elo).
*   **Resumo da Compra:** Mostra Quantidade, Preço por token e Total a pagar em BRL. Botão "Continuar".
*   **Pagamento PIX:** Exibe o Valor a Pagar, QR Code para escaneamento e Código PIX copia e cola. Botões "Copiar" e "Compartilhar". Instruções para pagamento.
*   **Confirmação de Pagamento:** Tela de sucesso indicando que os tokens serão creditados em breve.

### 🌱 Stake e Pools
*   **Tela Stake & Pools:** Visão geral com APY de staking destacado. Seção "Staking" com opções de período (30/180/365 dias) e multiplicadores. Botão "Fazer Stake". Listagem de Pools de Mineração e Pools de Liquidez disponíveis.
*   **Fazer Stake (Modal):** Inserir Quantidade (MCH), selecionar Duração (30/180/365 dias com APY correspondente), visualizar Recompensa Estimada. Botão "Confirmar Stake". Botão "MAX" para usar todo o saldo disponível.
*   **Operações de Stake (Modal):** Opções "Fazer Stake" e "Resgatar Stake".
*   **Resgatar Stake (Modal):** Exibe o Total em Stake. Lista os stakes ativos (com quantidade, data de término, APY). Checkboxes para selecionar quais stakes resgatar. Botões "Selecionar Todos" e "Limpar". Exibe o Total Selecionado e campo para Quantidade a Resgatar (com botão "MAX"). Botão "Confirmar Resgate".
*   **Detalhes Pool de Liquidez (Ex: MCH/BTC):** Modal para alocar MCH. Mostra Liquidez atual e APY. Campo para inserir quantidade. Botão "Confirmar Alocação".
*   **Detalhes Pool de Mineração (Ex: Gamma):** Modal para alocar MCH. Mostra número de Mineradores, Hashrate e Recompensa (%). Campo para inserir quantidade. Botão "Confirmar Alocação".

### 🏦 Carteira de Poupança
*   **Operações de Poupança (Modal):** Opções "Depositar" (Transferir da carteira principal para poupança) e "Resgatar" (Transferir da poupança para carteira principal).
*   **Depositar/Resgatar (Modal):** Campo para inserir Quantidade (MCH) com botão "MAX". Botões "Voltar" e "Confirmar".

### 📜 Histórico de Transações
*   **Últimas Transações (Home/Dashboard):** Lista resumida das transações mais recentes (Recebido, Enviado, Stake) com tipo, endereço/pool (parcial), valor e hora.
*   **Todas as Transações:** Tela dedicada com filtros por Tipo (Todas, Enviadas, Recebidas, Stakes, Recompensas) e Período (7d, 30d, 90d, 1 ano). Lista detalhada das transações.
*   **Detalhes da Transação (Modal):** Exibe ícone e tipo da transação (Ex: Stake, Recebido), data/hora, Quantidade, Endereço/Pool completo (com botão copiar), Taxas (Rede, Queima - se aplicável) e Status (Ex: Completed, Confirmado, Pendente).

### ⚙️ Configurações
*   **Aparência:** Toggle para ativar/desativar o "Tema Escuro".
*   **Notificações:** Toggle para ativar/desativar "Notificações Push".
*   **Segurança:** Opção para "Alterar Senha".
*   **Preferências:** Opção para selecionar o "Idioma" (mostrando Português).
*   **Suporte:** Links para "Central de Ajuda" e "Termos de Uso".
*   **Conta:** Botão "Sair da Conta".
*   **Informações:** Exibe a "Versão" do aplicativo e informações de Copyright (© 2025 MyChain).

---

## 🔧 Tecnologias Utilizadas

| Tecnologia        | Ícone | Descrição                                                               | Badge                                         |
| :---------------- | :---: | :---------------------------------------------------------------------- | :-------------------------------------------- |
| **React JS**      |   ⚛️   | Biblioteca JavaScript para construção de interfaces de usuário.         | [![React][react-shield]][react-url]           |
| **Meteor JS**     |   ☄️   | Plataforma full-stack para desenvolvimento web/mobile/desktop com JS. | [![Meteor][meteor-shield]][meteor-url]         |
| **Node.js**       |   🟩   | Ambiente de execução JavaScript server-side (via Meteor).             | [![Node.js][node-shield]][node-url]           |
| **MongoDB**       |   🍃   | Banco de dados NoSQL padrão do Meteor.                                | [![MongoDB][mongodb-shield]][mongodb-url]       |
| **HTML5 & CSS3**  | 🎨📑  | Estrutura e estilização da interface.                                 | [![HTML5][html5-shield]][html5-url] [![CSS3][css3-shield]][css3-url] |
| **JavaScript (ES6+)** |   <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JS" width="16"/> | Linguagem principal de programação. | [![JavaScript][js-shield]][js-url] |

*(Outras bibliotecas específicas do React ou Meteor podem estar em uso)*

---

## 🚦 Status Atual e Próximos Passos (Roadmap Preliminar)

*   **Versão Atual:** `v0.1` (MVP Experimental)
*   **Status:** 🟠 Em Desenvolvimento Ativo

**Foco Atual:**
*   Estabilização das funcionalidades MVP.
*   Correção de bugs identificados.
*   Refinamento da interface e experiência do usuário.
*   Melhorias na segurança e tratamento de erros.
*   Integração mais profunda com a blockchain MyChain.

**Possíveis Funcionalidades Futuras (Pós-MVP):**
*   [ ] Suporte a Múltiplas Contas/Perfis.
*   [ ] Integração com Hardware Wallets (Ledger, Trezor).
*   [ ] Suporte a NFTs (se aplicável ao ecossistema MyChain).
*   [ ] Funcionalidade de Swap/Exchange interna (se planejado).
*   [ ] Opções avançadas de segurança (2FA, Biometria).
*   [ ] Notificações push mais granulares.
*   [ ] Suporte a mais idiomas.
*   [ ] Otimizações de performance.
*   [ ] Programa de Beta Testing.

---

## ⚠️ Considerações Importantes

*   **Software Proprietário:** A MyChain Wallet é uma propriedade intelectual da Replika AI Solutions. Seu código-fonte não é aberto.
*   **Fase Experimental:** Por ser uma versão MVP (v0.1), a aplicação pode conter bugs ou instabilidades. Utilize por sua conta e risco.
*   **Segurança:** Embora a segurança seja uma prioridade, sempre adote as melhores práticas ao lidar com criptomoedas (senhas fortes, backups, etc.). **Nunca compartilhe suas chaves privadas ou frases de recuperação.**
*   **Sem Aconselhamento Financeiro:** A MyChain Wallet é uma ferramenta. Nenhuma informação apresentada constitui aconselhamento de investimento. Faça sua própria pesquisa (DYOR).

---

## 🤝 Contribuição

No momento, por ser um software proprietário e em fase inicial, as contribuições externas não estão abertas. Agradecemos o interesse! Para feedback ou reporte de bugs (na fase apropriada), entre em contato com a Replika AI Solutions.

---

## 📄 Licença

Este software é **proprietário** e distribuído sob os termos definidos pela Replika AI Solutions. Todos os direitos reservados.

[![License: Proprietary][license-shield]][license-url]

---

## 🏢 Desenvolvido Por

<img src="URL_DO_LOGO_REPLIKA_AI_SOLUTIONS_SE_TIVER" alt="Replika AI Solutions Logo" width="150"/>  <!-- Opcional: Adicione o logo -->

**Replika AI Solutions**
*   📍 Maringá, Paraná - Brasil 🇧🇷
*   💡 Fábrica de Software e Soluções de IA
*   📅 2025

---

<img width="431" alt="chrome_c7gZrcLfbh" src="https://github.com/user-attachments/assets/cc54c533-e56b-4ad7-a8ba-fd6b7a3da9fe" />

<img width="427" alt="chrome_eaOTZXoH9X" src="https://github.com/user-attachments/assets/f30dbae7-2d7d-4c81-9896-b4dc11fb7818" />

<img width="431" alt="chrome_osfBbenlz5" src="https://github.com/user-attachments/assets/51e18e83-cbc3-4b24-85f3-5be702d87dcb" />

<img width="431" alt="chrome_D8v8Eh6FUK" src="https://github.com/user-attachments/assets/192de5dc-61a1-4a3d-9029-ba8d67327ac7" />

<img width="431" alt="chrome_uri8S4tG2T" src="https://github.com/user-attachments/assets/7a937671-051f-4def-bb52-4ef1335395ea" />

<img width="431" alt="chrome_nZvc2kqXW1" src="https://github.com/user-attachments/assets/b4e355a0-979f-4e5a-a77f-677649d82b36" />

<img width="431" alt="chrome_MyaAjZ6h5D" src="https://github.com/user-attachments/assets/01d296ca-2120-4176-8e1e-3504ac029e6e" />

<img width="431" alt="chrome_tGnJmCBS3n" src="https://github.com/user-attachments/assets/b18986be-eee0-417e-bdb9-29fd16519ced" />

<img width="431" alt="chrome_Cyd1hHU86M" src="https://github.com/user-attachments/assets/9eb6d5bf-5113-4674-beb0-5f08c1877e01" />

<img width="431" alt="chrome_RHO3I3R8q3" src="https://github.com/user-attachments/assets/ff1c4893-88f1-4e94-91c6-fa5d32c2cef0" />

<img width="530" alt="chrome_ZnsH6TboCm" src="https://github.com/user-attachments/assets/d920e620-87ec-423a-a7ee-d683f9e6bd7e" />

<img width="530" alt="chrome_7QfRGsftNc" src="https://github.com/user-attachments/assets/dbcd45b5-bb31-40c3-b3b1-4fd93bc2e848" />

<img width="530" alt="chrome_6w4Pz9kPl2" src="https://github.com/user-attachments/assets/a85ca882-b033-4a43-815b-04c09caea532" />

<img width="291" alt="chrome_OhuetBdKJT" src="https://github.com/user-attachments/assets/af5d216a-f161-486d-a2a5-67c809fc5f4b" />

<img width="291" alt="chrome_oFML4b3onc" src="https://github.com/user-attachments/assets/1b3834a4-8abf-45b4-8122-f182e5be56cc" />

<img width="530" alt="chrome_mhc2BdQBts" src="https://github.com/user-attachments/assets/fe1e5e97-cbae-49e1-9b09-6fd477fb50f3" />

<img width="523" alt="chrome_dv0jcrQOg0" src="https://github.com/user-attachments/assets/53d15be2-77e7-4cce-9538-673b3aa2d2df" />

<img width="530" alt="chrome_VhIvXgdK72" src="https://github.com/user-attachments/assets/e7e67df7-92dc-4789-aae4-3e8e4ebad696" />

<img width="521" alt="chrome_LqXFuXPO6W" src="https://github.com/user-attachments/assets/3fb287a7-c536-4eb5-a8db-9d7a01cdeddc" />

<img width="530" alt="chrome_O1yODgsgFl" src="https://github.com/user-attachments/assets/b0251c2e-1a21-4611-af88-e758d7eb670e" />

<img width="530" alt="chrome_jQ3FjGAUXr" src="https://github.com/user-attachments/assets/48803332-6461-4961-9ba6-37589b5a3f0a" />

<img width="530" alt="chrome_EBgQzZnOJb" src="https://github.com/user-attachments/assets/01a7457b-146b-4137-941d-e0b47c1706e8" />

<img width="530" alt="chrome_OrJETqVf6E" src="https://github.com/user-attachments/assets/8ae97368-2b03-42ee-bedb-f8ab67df8321" />

<img width="530" alt="chrome_MddBXNhbCJ" src="https://github.com/user-attachments/assets/401309e4-f5ae-40c9-aa7d-a1f2e76ea79a" />

<img width="509" alt="chrome_efyvaeyxFk" src="https://github.com/user-attachments/assets/399ab15a-1d0e-4bc5-8161-3f7a7b720933" />

<img width="523" alt="chrome_NoSJRzf7O3" src="https://github.com/user-attachments/assets/69915761-c737-4d05-aa43-c1dc916f915a" />

<img width="530" alt="chrome_QNiYbFMZDA" src="https://github.com/user-attachments/assets/3e14330b-b206-4077-bc67-4da593e06b97" />

<img width="530" alt="chrome_9BXbGwMkCB" src="https://github.com/user-attachments/assets/8a38f8cb-f08a-4441-9539-3618b94bcd30" />

<img width="530" alt="chrome_k8L4Tcsjhp" src="https://github.com/user-attachments/assets/8ddf0969-a0a7-4961-b8b2-8a59e287fb20" />

<img width="530" alt="chrome_iuHVaYSODp" src="https://github.com/user-attachments/assets/673dde8e-d8ad-46b9-a314-103a496cf0f7" />

<img width="524" alt="chrome_JmgaJENm6g" src="https://github.com/user-attachments/assets/cfa8a406-936b-4161-9a6a-fa981bbd48e1" />

<img width="530" alt="chrome_ux7PWerUz2" src="https://github.com/user-attachments/assets/e0604a2d-cb86-41c4-96bb-4125b0c083b1" />

<img width="304" alt="chrome_NUYZFD9T3h" src="https://github.com/user-attachments/assets/0c94d055-e95d-47db-b9f3-d22f35b7f084" />

<img width="526" alt="chrome_GsTL9KDHes" src="https://github.com/user-attachments/assets/6ac9271d-b464-473d-8acc-5bb90c497481" />

<img width="525" alt="chrome_mxuR8ix3BQ" src="https://github.com/user-attachments/assets/735c2bfe-0656-47a2-8b6c-5cf91b5fe03e" />

<img width="300" alt="chrome_xTF8VNpxUA" src="https://github.com/user-attachments/assets/faf3883f-16b0-4cf7-a959-ffcd5348ea38" />

<img width="297" alt="chrome_jov4Igkug2" src="https://github.com/user-attachments/assets/c11cd234-64a8-4be9-8001-efce9cd92592" />

<img width="306" alt="chrome_yBUhA0RTM2" src="https://github.com/user-attachments/assets/d1f3e2f1-087f-431d-9f56-65079a8964e7" />

<img width="240" alt="chrome_j0nSDELtWo" src="https://github.com/user-attachments/assets/6b312aa1-98af-40a6-9028-bd5a9fc945e4" />

<img width="239" alt="chrome_z71iLdeyKc" src="https://github.com/user-attachments/assets/1b2d2993-4f42-48f0-a57d-ee5ffdf98ce2" />

<img width="242" alt="chrome_phNVhCwvMc" src="https://github.com/user-attachments/assets/5a2d4bcb-4a4f-4836-81df-8269f356e49e" />

<img width="238" alt="chrome_rApwCeIpXm" src="https://github.com/user-attachments/assets/17936eeb-4993-423a-b3d2-d044927f1fb2" />

<img width="241" alt="chrome_Jw1iYY1aNr" src="https://github.com/user-attachments/assets/5c675215-e71a-4d92-9739-e7a32b368508" />

<img width="530" alt="chrome_8UaLam5a3v" src="https://github.com/user-attachments/assets/d8d55f28-643d-40c4-8502-85c88b1b7952" />

<img width="528" alt="chrome_O1zUxXmxez" src="https://github.com/user-attachments/assets/ea3d1e54-ae23-4be2-bae9-b18640672fbb" />

<img width="526" alt="chrome_0Uk5AObcFA" src="https://github.com/user-attachments/assets/e4aa0a5b-ef1d-472b-b3ab-e97a1d3d96c3" />

<img width="530" alt="chrome_RfZbqmtc8N" src="https://github.com/user-attachments/assets/915f5951-12d3-40e8-926c-1a89bf081eed" />

<img width="521" alt="chrome_3Sd3wAvoXO" src="https://github.com/user-attachments/assets/f8cf5256-2f18-41b8-b82b-f17c26db2a60" />

<img width="530" alt="chrome_JiYlMvFerX" src="https://github.com/user-attachments/assets/97f90249-b814-4c89-8c15-c3976d0856b3" />

<img width="530" alt="chrome_GYjzKp1Cm7" src="https://github.com/user-attachments/assets/22ab0935-5993-4c7b-a605-04b1ccd018a0" />

<img width="525" alt="chrome_3DiKlb3CVQ" src="https://github.com/user-attachments/assets/6740772c-2c18-42e1-bb96-1999a91ade50" />

<img width="520" alt="chrome_w9aYIAkAJP" src="https://github.com/user-attachments/assets/ee7522a3-de5f-4be8-8588-c6543667095e" />

<img width="326" alt="chrome_x0f810dZKm" src="https://github.com/user-attachments/assets/3c26cd12-75a5-4e39-bc48-e3ad56f7cd77" />

<img width="527" alt="chrome_N2hOG0yk9K" src="https://github.com/user-attachments/assets/65b074a9-bbf3-4612-825e-211c8a407485" />

<img width="513" alt="chrome_R6mAheid1l" src="https://github.com/user-attachments/assets/f8d4e1cf-eb13-45b0-88d7-38abaeaa215e" />

<img width="525" alt="chrome_88znHXL74S" src="https://github.com/user-attachments/assets/59b8f1fc-0a1d-4aa0-acd4-955716341bbe" />

<img width="528" alt="chrome_hSpWrP95rI" src="https://github.com/user-attachments/assets/902e48bd-15bb-4127-a860-c55e22bf29c6" />

<img width="530" alt="chrome_XDhxqreyMF" src="https://github.com/user-attachments/assets/744e4141-80e4-4806-98cf-452e0677aaf4" />

<img width="523" alt="chrome_umQxvBMkQS" src="https://github.com/user-attachments/assets/fd410a53-3e09-4c40-8130-b7128ff78c66" />

<img width="528" alt="chrome_BUbYx7r9XE" src="https://github.com/user-attachments/assets/47f5811c-cbfb-4139-8621-0a001d027b40" />

<img width="421" alt="chrome_HcNr25OxOp" src="https://github.com/user-attachments/assets/14202520-59da-4293-a38d-456a9742fefc" />

<img width="508" alt="chrome_PE3g1XOtRr" src="https://github.com/user-attachments/assets/5e8d7892-6a22-4784-b24d-228242f04163" />

<img width="530" alt="chrome_gBc3pXSHW4" src="https://github.com/user-attachments/assets/46182c77-7e58-4ca5-9ea9-c6282aef420e" />

<img width="508" alt="chrome_wBn1V2EB5S" src="https://github.com/user-attachments/assets/ebf0fab8-dc9d-4e5a-bbe1-4a6484c477fc" />

<img width="530" alt="chrome_JiTLk6F3Je" src="https://github.com/user-attachments/assets/30312cd1-8402-4eb8-8742-c024462b7f32" />

<img width="525" alt="chrome_QySdis0pac" src="https://github.com/user-attachments/assets/7d883d26-aba7-4e45-bd9b-f94857450552" />

<img width="530" alt="chrome_o3oqc1xHIT" src="https://github.com/user-attachments/assets/8d47c3ef-0afd-477b-a517-ae33c7381fb8" />

<img width="305" alt="chrome_jut2QNQ10h" src="https://github.com/user-attachments/assets/ed6674d3-03d7-4e8f-b0bf-5969c2681c79" />

<img width="298" alt="chrome_cyOPEKvnES" src="https://github.com/user-attachments/assets/918c9984-fbb3-4ff3-9cda-6fc7df2fb068" />

<img width="530" alt="chrome_ecq1gdi73i" src="https://github.com/user-attachments/assets/eff15441-db4c-4df4-bf73-769fafd2aaa3" />

<img width="530" alt="chrome_G5HVSfznpv" src="https://github.com/user-attachments/assets/e41072db-c1f9-4f7b-983f-c0579a560b68" />

<img width="530" alt="chrome_DYhHZK0UkA" src="https://github.com/user-attachments/assets/ed681822-7849-4c13-9ecb-108f8cd567bd" />

<img width="530" alt="chrome_4ZmKeSn5UO" src="https://github.com/user-attachments/assets/08dd6794-2e6a-42e8-99fe-09d845e6871d" />

<img width="530" alt="chrome_AA2LxtLznt" src="https://github.com/user-attachments/assets/91905342-d5cd-498f-8def-89ad7fbd71f6" />

<!-- Shields/Badges Definitions (Orange Theme: #F39C12, #E67E22) -->
[react-shield]: https://img.shields.io/badge/React-^18.x-F39C12?style=for-the-badge&logo=react&logoColor=black
[react-url]: https://reactjs.org/
[meteor-shield]: https://img.shields.io/badge/Meteor_JS-^2.x-F39C12?style=for-the-badge&logo=meteor&logoColor=white
[meteor-url]: https://www.meteor.com/
[version-shield]: https://img.shields.io/badge/Version-0.1_MVP-E67E22?style=for-the-badge
[version-url]: #
[status-shield]: https://img.shields.io/badge/Status-Experimental-E67E22?style=for-the-badge
[status-url]: #
[license-shield]: https://img.shields.io/badge/License-Proprietary-E67E22?style=for-the-badge
[license-url]: #
[maintainer-shield]: https://img.shields.io/badge/Maintainer-Replika_AI_Solutions-E67E22?style=for-the-badge
[maintainer-url]: # COLOCAR_LINK_DA_REPLIKA_SE_TIVER
[last-commit-shield]: https://img.shields.io/github/last-commit/SEU_USUARIO_GITHUB/SEU_REPOSITORIO_MYCHAIN_WALLET?color=E67E22&style=for-the-badge
[last-commit-url]: https://github.com/SEU_USUARIO_GITHUB/SEU_REPOSITORIO_MYCHAIN_WALLET/commits/main
[node-shield]: https://img.shields.io/badge/Node.js-LTS-F39C12?style=for-the-badge&logo=node.js&logoColor=white
[node-url]: https://nodejs.org/
[mongodb-shield]: https://img.shields.io/badge/MongoDB- ব্যবহৃত -F39C12?style=for-the-badge&logo=mongodb&logoColor=white
[mongodb-url]: https://www.mongodb.com/
[html5-shield]: https://img.shields.io/badge/HTML5-Utilized-F39C12?style=for-the-badge&logo=html5&logoColor=white
[html5-url]: https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5
[css3-shield]: https://img.shields.io/badge/CSS3-Utilized-F39C12?style=for-the-badge&logo=css3&logoColor=white
[css3-url]: https://developer.mozilla.org/en-US/docs/Web/CSS
[js-shield]: https://img.shields.io/badge/JavaScript-ES6+-F39C12?style=for-the-badge&logo=javascript&logoColor=black
[js-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript
