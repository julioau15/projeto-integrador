# Documentação - Servidor DNS
- Julio Augusto Barbosa da Silva
- Alice Campos da Silva
- Leandro dos Reis Filho
## Entrar no modo de super usuário:
- su
## Atualizar dependências:
- sudo apt update
## Instalar Bind9:
- sudo apt intall bind9
## Criar Zona:
- nano /etc/bind/named.conf.local <br>
 <img width="727" height="480" alt="image" src="https://github.com/user-attachments/assets/b69460ea-333c-4273-87d4-aef8aa9a3e7e" />

## Configurar DNS:
- nano /var/lib/bind/db.estaciona.com.br <br>
<img width="727" height="485" alt="image" src="https://github.com/user-attachments/assets/ce48b36f-a0ed-49e2-9542-2ce8d043a284" />

## Atualizar serviço:
- sudo systemctl restart bind9