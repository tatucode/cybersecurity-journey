# Crocodile

## Plataforma 
Hack The Box

## Dificuldade
Very Easy

## Ferramentas 
- Nmap
- FTP

## Aprendizados
- Identifiquei os serviços disponíveis através de enumeração com Nmap;
- Identifiquei que o FTP permitia acesso anônimo;
- Encontrei arquivos contendo possíveis credenciais através do FTP;
- Descobri a página de login na aplicação web;
- Utilizei as credenciais encontradas para acessar o painel de administrador e recuperar a flag.

## Comandos utilizados
- `nmap -sC -sV <IP>`
- `FTP <IP>`
- `get <arquivo>`

## Conceitos praticados
- Enumeração de serviços;
- FTP;
- Acesso anônimo;
- Enumeração de arquivos;
- Exposição de credenciais;
- Autenticação web.

## Mitigações
- Desabilitar acesso anônimo ao FTP;
- Não armazenar credenciais em arquivos expostos;
- Restringir acesso aos serviços
- Implementação e utilização de autenticação multifator

## Tempo de resolução
25 minutos

## Data
13-09-2026

## Imagens
<img width="669" height="458" alt="Captura de tela_2026-09-11_21-59-43" src="https://github.com/user-attachments/assets/cc639c3f-23a7-46c7-91e0-8bb87b88bb12" />

<img width="1366" height="768" alt="Captura de tela_2026-09-11_21-58-09" src="https://github.com/user-attachments/assets/75f01f2c-284b-45f1-9fa0-42104c068f7e" />

