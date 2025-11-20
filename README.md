# Atividade N1 & N2

```
Sistema de Entrega Rapida de Drones

```

## Nomes
Daniel Zacharias Bittar Atui - 10410051

## Requisitos

### Funcionais

ID,Nome do Requisito,Descrição
RF001,Manter Usuários (Clientes),"O sistema deve permitir o cadastro, login e edição de dados dos clientes que solicitam entregas. Dados necessários: Nome, CPF, Endereço com geolocalização e cartão de crédito."
RF002,Manter Funcionários,O sistema deve permitir o cadastro de operadores que controlam a frota. Apenas o administrador (Sr. Hélice) pode cadastrar novos operadores.
RF003,Gerenciar Drones,"O sistema deve manter um registro de cada drone, contendo número de série, capacidade de carga, modelo e status atual (Disponível, Em Rota, Em Manutenção)."
RF004,Solicitar Entrega,O cliente deve conseguir solicitar uma entrega informando o tamanho do pacote e o destino. O sistema deve verificar se há drones disponíveis.
RF005,Calcular Rota e Frete,"Antes de confirmar o pedido, o sistema deve calcular a distância, o tempo estimado e o valor do frete baseado na complexidade da rota urbana."
RF006,Rastreamento em Tempo Real,O sistema deve exibir para o cliente e para o operador a localização atual do drone durante uma entrega ativa.
RF007,Monitoramento de Bateria,"O sistema deve alertar o operador caso a bateria de um drone em rota caia abaixo de 15%, sugerindo retorno imediato ou pouso de emergência."
RF008,Histórico de Entregas,O sistema deve gerar relatórios de todas as entregas realizadas para controle financeiro e logístico.

### Não Funcionais

ID	Categoria	Descrição
RNF001	Desempenho	O rastreamento do drone deve ter uma latência máxima de 5 segundos para garantir precisão na localização.
RNF002	Usabilidade	O sistema deve possuir uma interface responsiva (Web e Mobile), focada na facilidade de uso para o operador logístico.
RNF003	Segurança	As senhas dos usuários devem ser criptografadas no banco de dados (padrão hash). Dados de pagamento não devem ser salvos, apenas o token da transação.
RNF004	Disponibilidade	O sistema deve operar 24/7, com disponibilidade mínima de 99% durante o horário comercial.
RNF005	Restrições Legais	O sistema deve respeitar as normas da LGPD (Lei Geral de Proteção de Dados) no tratamento dos dados dos clientes.
RNF006	Hardware	O software de controle deve ser compatível com o protocolo de comunicação dos drones modelo X-Wing 500 (invente um modelo aqui para personalizar).

Link do Diagrama: https://drive.google.com/file/d/1HKvvxCnwcIfksb307WtYeiy3SvW8MQrk/view?usp=sharing
