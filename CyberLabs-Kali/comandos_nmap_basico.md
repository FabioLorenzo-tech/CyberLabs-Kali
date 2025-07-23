# Comandos básicos do Nmap para varredura de portas

## 1. Escanear portas abertas em um alvo
`nmap <IP-ou-Domínio>`

## 2. Escanear portas específicas
`nmap -p <portas> <IP-ou-Domínio>`  
Exemplo: `nmap -p 22,80 <IP-ou-Domínio>`

## 3. Escanear uma faixa de portas
`nmap -p <início>-<fim> <IP-ou-Domínio>`  
Exemplo: `nmap -p 1-100 <IP-ou-Domínio>`

## 4. Escanear várias máquinas (IP range)
`nmap 192.168.1.1-50`  
ou  
`nmap 192.168.1.0/24`

## 5. Escanear com detecção de sistema operacional e serviços
`nmap -A <IP-ou-Domínio>`

## 6. Escanear com modo silencioso (stealth scan)
`nmap -sS <IP-ou-Domínio>`

## 7. Escanear com detecção de versão dos serviços
`nmap -sV <IP-ou-Domínio>`

## 8. Escanear todas as portas (1 a 65535)
`nmap -p- <IP-ou-Domínio>`

## 9. Salvar o resultado em arquivo
- Formato normal:  
  `nmap -oN resultado.txt <IP-ou-Domínio>`
- Formato XML:  
  `nmap -oX resultado.xml <IP-ou-Domínio>`
- Formato grepable:  
  `nmap -oG resultado.gnmap <IP-ou-Domínio>`

## 10. Escanear usando scripts específicos (Nmap Scripting Engine)
`nmap --script <nome-do-script> <IP-ou-Domínio>`  
Exemplo: `nmap --script ssl-enum-ciphers <IP-ou-Domínio>`
