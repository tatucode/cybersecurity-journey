# Redeemer

## Plataforma
Hack The Box

## Dificuldade
Very Easy

## Ferramentas
- Nmap.
- Redis CLI.

## Aprendizados
- Identifiquei o serviço Redis através da enumeração com Nmap.
- Aprendi que o Redis é um banco de dados NoSQL em memória.
- Conectei ao serviço utilizando o cliente `redis-cli`.
- Utilizei o comando `INFO` para coletar informações sobre a instância do Redis, como versão, configuração e estatísticas do servidor
- Enumerei as chaves armazenadas no banco de dados.
- Recuperei a flag através da leitura de uma chave existente.

## Comandos utilizados
- `nmap -p- --min-rate 1000 -T4 <IP>`
- `redis-cli -h <IP>`
- INFO
- KEYS *
- GET flag

## Conceitos praticados
- Enumeração de serviços.
- Redis.
- Banco de dados NoSQL.
- Enumeração de chaves.
- Serviços expostos.

## Mitigações
- Configurar autenticação (requirepass).
- Restringir o acesso ao Redis apenas para os hosts autorizados.
- Manter o Redis atualizado.
- Monitorar acessos e limitar a exposição do serviço.

## Tempo de resolução
40 minutos

## Data
02-08-2026
