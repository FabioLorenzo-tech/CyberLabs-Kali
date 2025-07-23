# Comandos básicos do terminal Kali Linux

## 1. Navegação de diretórios
- `pwd` — mostra o diretório atual
- `ls` — lista arquivos e pastas do diretório atual
- `ls -l` — lista detalhada (permissões, dono, tamanho)
- `cd <diretório>` — muda para o diretório especificado
- `cd ..` — sobe um nível no diretório
- `cd ~` — vai para o diretório home

## 2. Manipulação de arquivos e pastas
- `touch <arquivo>` — cria um arquivo vazio
- `mkdir <pasta>` — cria uma pasta
- `rm <arquivo>` — remove um arquivo
- `rm -r <pasta>` — remove uma pasta e todo conteúdo dela
- `cp <origem> <destino>` — copia arquivos ou pastas
- `mv <origem> <destino>` — move ou renomeia arquivo/pasta
- `cat <arquivo>` — mostra conteúdo do arquivo
- `nano <arquivo>` — edita arquivo com editor simples

## 3. Permissões e usuários
- `chmod <permissões> <arquivo>` — muda permissões (ex: `chmod 755 arquivo`)
- `chown <usuário>:<grupo> <arquivo>` — muda dono e grupo
- `whoami` — mostra o usuário atual
- `sudo <comando>` — executa comando como administrador (root)

## 4. Gerenciamento de processos
- `ps aux` — lista todos processos em execução
- `top` — monitora processos em tempo real
- `kill <PID>` — termina processo pelo ID

## 5. Comandos de rede
- `ifconfig` ou `ip a` — mostra configurações de rede
- `ping <host>` — testa conectividade com um host
- `netstat -tulnp` — lista conexões de rede e serviços ativos
- `nmap <IP-ou-Domínio>` — escanear portas

## 6. Outros comandos úteis
- `clear` — limpa a tela do terminal
- `history` — mostra comandos executados recentemente
- `uname -a` — informações do sistema
- `df -h` — mostra espaço em disco usado e disponível
- `free -m` — mostra uso de memória RAM em MB
