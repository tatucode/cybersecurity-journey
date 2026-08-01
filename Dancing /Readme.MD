# Dancing

## Plataforma
Very Easy

## Ferramentas
- Nmap
- SMBClient

## O que eu aprendi
- Identifiquei o serviço SMB através de enumeração com Nmap.
- Aprendi o que o SMB permite compartilhamento de arquivos e recursos em sistemas Windows.
- Enumerei os compartilhamentos disponíveis no servidor.
- Acessei um compartilhamento sem autenticação.
- Localizei e capturei a flag.
- Reforcei a importância da enumeração antes de qualquer tentativa de exploração.

## Comandos utilizados
- nmap -sV <IP>
- smbclient -L \\<IP>
- smbclient "\\\\<IP>\\<compartilhamento>"

## Conceitos estudados
- Enumeração de serviços
- SMB (Server Message Block)
- Compartilhamento de rede
- Acesso anônimo (quando permitido)

## Mitigações
- Desabilitar acesso anônimo a compartilhamentos SMB.
- Aplicar o princípio de menor privilégio.
- Restringir os compartilhamentos desnecessários.
- Mantes o SMB atualizado e monitorado.

## Data
01-08-2026
