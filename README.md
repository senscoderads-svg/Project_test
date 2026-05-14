# Consulta de Saldo na Binance Smart Chain (BSC)

Este projeto é um script simples em Python que utiliza a biblioteca Web3 para monitora saldo de uma carteira específica na rede Binance Smart Chain (BSC). Ele verifica o saldo de BNB nativo e do token USDT (Tether) em uma carteira pré-configurada.

## Funcionalidades

- Conecta-se à rede BSC via um nó público da Binance.
- Obtém o número do bloco atual da rede.
- Consulta o saldo de BNB nativo da carteira.
- Consulta o saldo do token USDT da carteira.
- Exibe os resultados de forma clara e legível.

## Pré-requisitos

- Python 3.11.0 ou superior instalado.
- Conexão com a internet para acessar a rede BSC.

## Instalação

1. Clone ou baixe este repositório.
2. Navegue até o diretório do projeto.
3. Instale as dependências executando o comando:

   ```
   pip install -r requirements.txt
   ```

## Uso

Execute o script principal com o comando:

```
python main.py
```

O script irá conectar à BSC, consultar os saldos e mostrar as informações no terminal.

## Dependências

- `web3==6.15.1`: Biblioteca para interagir com a blockchain Ethereum/BSC.
- `python-dotenv==1.0.1`: Biblioteca para gerenciar variáveis de ambiente (não utilizada no script atual, mas incluída para futuras expansões).

## Observações

- O script utiliza uma carteira pública de exemplo da Binance. Para usar com sua própria carteira, modifique as constantes `WALLET_ADDRESS` e `TOKEN_ADDRESS` no arquivo `main.py`.
- Certifique-se de que a conexão com a internet esteja estável, pois o script depende de um nó RPC público.

## Licença

Este projeto é distribuído sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.