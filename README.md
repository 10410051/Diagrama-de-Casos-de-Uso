# Atividade N1 & N2

## Sistema de Entrega Rapida de Drones

## Nomes

Daniel Zacharias Bittar Atui - 10410051
Lucas Assis - 10735712

---

## Requisitos Funcionais

### Gerenciar Usuários

O sistema deve permitir o cadastro, autenticação (login) e edição de dados dos clientes.
As informações obrigatórias incluem: nome completo, CPF, endereço com geolocalização e dados de pagamento (armazenados apenas via token de transação).

### Gerenciar Funcionários

O sistema deve permitir o cadastro e manutenção dos dados dos operadores da frota.
Somente o administrador (Sr. Hélice) possui permissão para cadastrar novos operadores.

### Gerenciar Drones

O sistema deve manter um registro completo dos drones, contendo: número de série, modelo, capacidade de carga e status operacional (Disponível, Em Rota ou Em Manutenção).

### Solicitar Entrega

O cliente deve conseguir solicitar uma entrega informando o tamanho/volume do pacote e o destino.
O sistema deve verificar automaticamente a disponibilidade de drones antes de confirmar o pedido.

### Calcular Rota e Frete

O sistema deve calcular, antes da confirmação da entrega, a distância estimada, o tempo previsto e o valor do frete, considerando a complexidade da rota urbana.

### Rastreamento em Tempo Real

O sistema deve disponibilizar, para clientes e operadores, o rastreamento da localização do drone em tempo real durante entregas ativas.

### Monitoramento de Bateria

O sistema deve alertar o operador caso o nível de bateria de um drone em operação seja inferior a 15%, sugerindo retorno imediato ou pouso de emergência.

### Histórico e Relatórios de Entregas

O sistema deve armazenar e disponibilizar um histórico completo das entregas concluídas, permitindo a geração de relatórios financeiros e logísticos.

---

## Requisitos Não Funcionais

### Desempenho

O rastreamento do drone deve apresentar latência máxima de 5 segundos, garantindo precisão e atualizações confiáveis da posição.

### Usabilidade

O sistema deve oferecer uma interface responsiva, acessível via Web e Mobile, com foco na facilidade de uso para clientes e operadores.

### Segurança

As senhas dos usuários devem ser criptografadas por meio de algoritmo de hash.
Dados de pagamento não podem ser armazenados pelo sistema — apenas o token da transação deve ser mantido.

### Disponibilidade

O sistema deve operar 24 horas por dia, 7 dias por semana, com disponibilidade mínima de 99% durante o horário comercial.

### Conformidade Legal

O sistema deve atender à LGPD (Lei Geral de Proteção de Dados), garantindo proteção e tratamento adequado das informações pessoais dos usuários.

### Compatibilidade de Hardware

O sistema deve ser totalmente compatível com o protocolo de comunicação dos drones modelo **X-Wing 500** (modelo fictício adotado para padronização do projeto).

---

## Diagrama de Casos de Uso 

<img width="784" height="885" alt="plantuml" src="https://github.com/user-attachments/assets/b8f6cbf5-a699-4769-9579-425de08eae15" />

