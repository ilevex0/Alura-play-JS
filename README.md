# Alura-play-JS

## Dependências e Configuração

Este projeto usa algumas dependências e comandos específicos que devem ser configurados e executados para funcionar corretamente.

### Dependências

1. **json-server**

   Instale `json-server` globalmente usando o npm:

   ```bash
   npm install json-server
   
# Verifique a política de execução atual
Get-ExecutionPolicy

# Se necessário, defina a política para RemoteSigned
Set-ExecutionPolicy RemoteSigned

# Iniciar o json-server

Para iniciar o `json-server` e observar o arquivo db.json, execute o seguinte comando no terminal:
```bash
json-server --watch db.json
