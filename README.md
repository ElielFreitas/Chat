# Projeto Chat em Java
Este é um sistema de chat simples implementado em Java utilizando sockets. O projeto consiste em dois componentes principais: um servidor e um cliente, que se comunicam através de conexões de rede para permitir a troca de mensagens em tempo real.

## Funcionalidades
### Servidor
- Aceitação de Conexões: O servidor aceita conexões de múltiplos clientes através de sockets.
- Gerenciamento de Clientes: Utiliza uma lista para armazenar os clientes conectados, permitindo a transmissão de mensagens para todos eles.
- Broadcast de Mensagens: As mensagens enviadas por um cliente são retransmitidas para todos os outros clientes conectados, exceto o remetente.
- Manejo de Exceções: Inclui tratamento básico de exceções para garantir a robustez do servidor.
### Cliente
- Interface Gráfica (GUI): Utiliza Swing para criar uma interface amigável e intuitiva.
- Envio e Recepção de Mensagens: Os clientes podem enviar mensagens e visualizar as mensagens recebidas de outros usuários em tempo real.
- Conexão com o Servidor: Permite que o usuário especifique o IP e a porta do servidor para estabelecer a conexão.
- Desconexão: Os usuários podem se desconectar do servidor de forma graciosa, enviando uma mensagem de saída.
### Tecnologias Utilizadas
- Java: Linguagem de programação principal utilizada para implementar tanto o servidor quanto o cliente.
- Sockets: Utilizados para comunicação de rede entre o servidor e os clientes.
- Swing: Biblioteca gráfica utilizada para criar a interface do cliente.
### Como Funciona
- Iniciar o Servidor: O servidor é iniciado especificando uma porta para escutar as conexões dos clientes.
- Conectar o Cliente: O cliente se conecta ao servidor através do IP e porta especificados.
- Troca de Mensagens: Uma vez conectado, o cliente pode enviar mensagens que são retransmitidas para todos os outros clientes conectados.
- Desconectar: Os clientes podem se desconectar enviando uma mensagem "Sair", e o servidor encerra a conexão de forma segura.
## Configuração
### Requisitos
- Java Development Kit (JDK) instalado.
### Passos para Compilar e Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/SeuUsuario/SeuRepositorio.git
2. Copiar código:
   git clone https://github.com/SeuUsuario/SeuRepositorio.git
4. Compile e execute o servidor:
Copiar código
cd ProjetoChat
javac ServidorSocket.java
java ServidorSocket
5. Compile e execute o cliente:
bash
Copiar código
javac ClientSocket.java
java ClientSocket
## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para melhorias e correções.

Contato
Sinta-se à vontade para me contatar via LinkedIn para discutir este projeto ou qualquer outra ideia!
