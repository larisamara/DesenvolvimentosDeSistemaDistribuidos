# DesenvolvimentosDeSistemaDistribuidos

# Sistema Distribuído com gRPC: Python Cliente e Node.js Servidor

## Este projeto é um exemplo de sistema distribuído utilizando gRPC, onde:

### Um servidor em Node.js recebe arquivos enviados pelo cliente.
### Um cliente em Python envia arquivos para o servidor.

### Arquitetura do Sistema
### O sistema utiliza o protocolo gRPC para comunicação entre o cliente e o servidor.
### O Protobuf é usado para definir as mensagens e os métodos disponíveis para a comunicação.

# Gerar os arquivos gRPC

### comando  (python -m grpc_tools.protoc -I. --python_out=. --grpc_python_out=. file_transfer.proto)

### Exemplos de Uso

execute no terminal: `node server.js`

```bash
# saida esperada
Servidor executando na porta 50051
```


execute no terminal: `python client.py`
```bash
Entre com o nome do arquivo para fazer o upload: teste.txt

Arquivo upload-teste.txt carregado com sucesso!
```
