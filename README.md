# ⛩️ Dojo [Template]

## TLDR

### Numbers

| participants | projects | challenger |
| ------------ | -------- | ---------- |
| 0            | 0        | 0          |

### Participants Posts

-
-
-

## Opening Video

## Challenger

### 1: Explorer Challenger

> [!CAUTION]
> must have

- Deploy online de um Explorer que deve:
- Buscar um bloco pelo número.
- Buscar uma transação pelo hash.
- Buscar o saldo pelo endereço.
- Conectar com a mainnet.

> [!IMPORTANT]
> should have

- Frontend atualizado a cada novo bloco.
- Exibir detalhes avançados de transações (ex.: inputs/outputs, scripts, etc.).
- Suporte para múltiplas redes (mainnet, testnet, etc.).

> [!TIP]
> could have

- Subir um fullnode [BLOCKCHAIN_NAME] em algum Cloud.
- Conectar o Explorer ao seu fullnode, como uma rede privada.
- Adicionar gráficos e estatísticas (ex.: hash rate, transações por segundo).

<img src="" alt="Blockchain Explorer" width="400">

### 2: Wallet Challenger

> [!CAUTION]
> must have

- Criar uma Wallet web que:
- Gere um par de chaves.
- Importe seed para criar wallet.
- Busque o saldo da carteira.
- Envie [NATIVE_TOKEN] para outros endereços.

> [!IMPORTANT]
> should have

- Importar seed de 12 e 24 palavras.
- Importar private keys.
- Buscar saldo de outros tokens.
- Enviar qualquer token.

> [!TIP]
> could have

- Salvar de forma segura a wallet no disco usando o padrão: Web3 Secret - Storage Definition.
- Adicionar suporte para assinatura de mensagens e transações offline.

<img src="" alt="Wallet Challenger" width="400">

### 3: Oracle Challenger

> [!CAUTION]
> must have

- Interface frontend onde o usuário:
- Adiciona seu nome e links para LinkedIn, GitHub e X (Twitter).
- Assina e paga para adicionar seus dados on-chain.
- Qualquer pessoa pode dar 1 estrela para esse usuário.
- Para dar uma estrela, outro usuário assina e paga.
- As estrelas funcionam como reputação recebida da comunidade.
- Exibir um ranking de usuários com maior reputação.

> [!IMPORTANT]
> should have

- Implementar um mecanismo de incentivo para prevenir fraudes (ex.: custo para dar estrelas aumenta exponencialmente).
- Limitar o número de estrelas que um usuário pode dar por dia.

> [!TIP]
> could have

- Adicionar um sistema de recompensas para usuários com alta reputação (ex.: tokens ou badges).
- Permitir que usuários adicionem outros perfis sociais ou habilidades.
- Integrar com um sistema de governança onde usuários com alta reputação têm mais peso em votações

<img src="" alt="Oracle Challenger" width="400">

### 4: Smartcontracts Challenger: Token ERC20 Like

> [!CAUTION]
> must have

- Criar um contrato de token compatível com o padrão ERC-20 (ou equivalente na blockchain escolhida).
- Implementar funções básicas: transfer, balanceOf, approve, e transferFrom.
- Permitir o minting e burning de tokens.
- Interface frontend para qualquer um poder mintar e ganhar tokens.

> [!IMPORTANT]
> should have

- Adicionar eventos para transferências e aprovações.
- Implementar um sistema de taxas para transações.

> [!TIP]
> could have

- Permitir a pausa e retomada de transações (se suportado pela blockchain).
- Interface (se user tiver tokens) mostra dashboard com saldo

<img src="" alt="Smartcontracts Challenger: Token ERC20 Like" width="400">

### 5: Smartcontracts Challenger: Voting System

> [!CAUTION]
> must have

- Criar um sistema de votação simples onde:
- Uma eleição dura 7 dias (contado em blocos).
- O período de votação dura 1 dia (contado em blocos).
- Qualquer um pode se candidatar para a eleição atual (se já houver um eleito, será candidato para a próxima).
- Qualquer um pode votar 1 vez nos candidatos.
- Exibir resultados em tempo real.

> [!IMPORTANT]
> should have

- Permitir votação ponderada com base em tokens ou reputação.

> [!TIP]
> could have

- Implementar um mecanismo de incentivo para prevenir fraudes (ex.: custo para votar ou recompensas para votantes).
- Adicionar um sistema de delegação de votos.

<img src="" alt="Smartcontracts Challenger: Voting System" width="400">

### 6: Smartcontracts Challenger: DeFi Zero-Collateral Lending

> [!CAUTION]
> must have

- Usar o oráculo criado anteriormente para liberar empréstimos sem colateral.
- Permitir que usuários com alta reputação peguem empréstimos.
- Criar um sistema de pagamento de empréstimos com juros.

> [!IMPORTANT]
> should have

- Implementar um sistema de penalidades para inadimplência. (bot que comenta nas redes sociais algo negativo, etc)
- Permitir que investidores forneçam liquidez para os empréstimos.
- Criar pools de liquidez com diferentes níveis de risco (ex.: AAA, BBB, CCC).

> [!TIP]
> could have

- Adicionar um sistema de seguro para investidores.
- Permitir a tokenização dos empréstimos (ex.: NFTs representando - dívidas).

<img src="" alt="Smartcontracts Challenger: DeFi Zero-Collateral Lending" width="400">

### 7: Smartcontracts Challenger: Hack me!

> [!CAUTION]
> must have

- O professor escreve um contrato com 8 falhas de desenvolvimento:
- 2 falhas críticas (ex.: reentrância, overflow).
- 2 falhas médias (ex.: lógica incorreta, permissões inadequadas).
- 4 falhas baixas (ex.: eventos ausentes, má documentação).
- Fornecer dicas para os alunos encontrarem as falhas.
- Criar um sistema de pontuação baseado na gravidade das falhas encontradas.
- Permitir que os alunos expliquem as falhas e como corrigi-las.
- Adicionar um sistema de recompensas para os alunos que encontrarem as - falhas.
- Criar uma competição em tempo real durante a seção ao vivo.
- Publicar um relatório pós-desafio com as falhas e correções.

<img src="" alt="Smartcontracts Challenger: Hack me!" width="400">

## Links utils

-
-
-
