# Sequel

## Plataforma 
Hack The Box

## Dificuldade
Very Easy

## Ferramentas 
Nmap
MySQL

## Aprendizados
- Utilizando o Nmap descobri que o `MySQL` roda na porta 3306
- Descobri o parâmetro `-sC` no Nmap que junto do `sV` traz identificação de versões e roda scripts padrão para varreduras mais profundas
- Aprendi o uso do `root` no `MariaDB` para acessar sem precisar de senha

## Conceitos praticados
- Enumeração de serviços
- Banco de dados MySQL
- Acesso root no MariaDB
- Acesso remoto ao banco de dados

## Mitigações
- Definir uma senha forte para o usuário Root (Autenticação obrigatória)
- Desabilitar o acesso remoto ao banco de dados
- Implementar regras de Firewall (Caso seja extremamente necessário que o banco de dados receba conexões externas)

## Tempo de resolução
41 minutos 

## Data
06-09-2026

## Imagens
<img width="616" height="324" alt="image" src="https://github.com/user-attachments/assets/3f35dd4d-8744-4d4a-a3a4-19de44e354d2" />

<img width="855" height="535" alt="image" src="https://github.com/user-attachments/assets/616b7d2d-eda5-490a-ba94-8aba2842c3db" />

