# Criação de uma Instância SQL na Azure

Durante o processo de criação de uma instância SQL no Azure, algumas etapas e configurações são essenciais:

## Etapas Iniciais

- **Nome da instância**  
  Identificador único da instância SQL.

- **Assinatura (Subscription)**  
  Define a conta que será responsável pelo faturamento.

- **Região (Location)**  
  Local físico onde o recurso será provisionado.

- **Tipo de autenticação**  
  Pode-se escolher entre:
  - Autenticação SQL (login e senha)
  - Autenticação integrada com Azure AD

- **Credenciais de administrador**  
  Definição do login e senha do administrador do servidor SQL.

---

## Configuração do Banco de Dados

Após a criação da instância, é possível configurar o banco de dados com:

- **Poder de processamento (DTUs ou vCores)**  
  Escolha baseada em performance e escalabilidade desejada.

- **Capacidade de armazenamento**  
  Tamanho máximo de armazenamento que o banco poderá utilizar.

- **Tipo de licença**  
  Escolha entre:
  - Com licença incluída (licenciamento pago junto com o serviço)
  - Benefício de licenciamento híbrido (para quem já possui SQL Server)

- **Redundância de armazenamento**  
  Define a replicação dos dados (LRS, ZRS, GRS).

---

## Configurações de Rede e Segurança

- **Rede virtual (VNet)**  
  Permite associar o banco a uma rede específica, com regras de segurança mais rígidas.

- **Regras de firewall e permissões de acesso**  
  Configuração de IPs permitidos e grupos de segurança.

- **Tipos de conexão**  
  Pode-se permitir conexões públicas, privadas ou via endpoints dedicados.

---

> 🛡️ A correta configuração da instância SQL na Azure garante desempenho, segurança e escalabilidade para as aplicações que dependem do banco de dados.
