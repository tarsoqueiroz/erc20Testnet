# ERC-20 em Testnet

Criação de um smartcontract ERC20 simples em Testnet.

## Metamask: carteira Web3

Links úteis:

- https://metamask.io/​
- https://rpc.info/

**Instalação do Metamask**:

Instalar a extensão do Metamask no Chrome/Brave.

**Criar a carteira**:

Salvar as palavras secretas que dão acesso à carteira.

> **NÃO REPASSAR ESSAS PALAVRAS A NINGUÉM**

Chave de recuperação secreta é uma espécie de **PIN** para proteção ao acesso direto e indesejado. Um nível a mais de proteção.

Criado inicialmente uma conta (`Account 1`) como sendo uma ***conta corrente*** nessa carteira. Outras podem ser criadas, adicionas e até mesmo adicionado um ***hardware wallet***.

Com conta `Account 1` temos associada a ela:

- Chave pública: é o endereço a ser utilizado nas transações.
- Chave privada: é a chave que acessa/confirma transações oriundas da chave pública.

## Holesky Testnet

- Network URL: **`https://ethereum-holesky.publicnode.com`**
- Chain ID: **`17000`**
- Currency symbol: **`ETH`**
- Block explorer URL: **`https://holesky.beaconcha.in`**
- Explorer by address: **`https://holesky.beaconcha.in/address/<address>`**

> Ref.: `https://www.coingecko.com/learn/holesky-testnet-eth`

## Faucet

Buscar para as redes de teste ***coins*** através de redes *Faucet* que distribuem. Para a rede Holesky utilizar:

> `https://holesky-faucet.pk910.de/`

## Criando o seu Token

Criação através do Remix:

- https://remix.ethereum.org/

Criar um novo workspace:

- `TAR_Workspace`

Criar um novo arquivo com o nome: `tokenERC20basic.sol`. Conteúdo está em [`tokenERC20basic.sol`](./tokenERC20basic.sol).

Utilizar a chave da conta a ser utilizada na rede de testes dentro do código acima. Para essa conta é que irão os **TQH coins**. Compilar e verificar se existe algum erro.

Na compilação verificar:

- Versão de compilação (`INSERIR VERSÃO AQUI`)

Para o deploy selecionar:

- Uma conta com saldo na rede Holesky.
- Verificar a conta em uso para deploy.

## Usando o contrato criado

...

