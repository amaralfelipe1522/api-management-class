# Gerenciamento e Estruturas de APIs

## 📌 Descrição

Este material faz parte da aula de Gerenciamento e Estruturas de APIs, incluindo configuração de ambientes Docker para diferentes tipos de APIs. Existem dois diretórios principais:

- **grpc/**: Para APIs baseadas em gRPC.
- **rest/**: Para APIs REST convencionais e GraphQL.

Todos os diretórios contêm um arquivo `docker-compose.yaml` para facilitar o provisionamento dos containers.

---

## 📦 Requisitos

Antes de iniciar, certifique-se de ter os seguintes softwares instalados:

- [Docker](https://www.docker.com/) e [Docker Compose](https://docs.docker.com/compose/)
- [VS Code](https://code.visualstudio.com/)
- Extensão **Docker** para VS Code
- [Thunder Client] (para testes de APIs REST)
- [vscode-proto3] (suporte ao Protobuf 3 no VS Code)

---

## 🚀 Como Executar

1. **Entre no diretório da aula ou do referencial**

   ```sh
   cd aula  # ou "cd referencial"
   ```

2. **Suba os containers**

   ```sh
   docker compose up -d
   ```

3. **Verifique os containers em execução**

   ```sh
   docker ps
   ```

4. **Acesse as APIs**

   - Para REST, use o Thunder Client ou o `curl`

5. **Para parar os containers**
   ```sh
   docker compose down
   ```

---

ANXM6t4xZAf9ZEyxzmm9hV3QIh2yyUcGrLAETanmSNyhHQKrrGmWNM7jeEJp6HGL
UJNh8X3fjezxXIFJRPIf2QFFjRFsfyA3DLMRpTQbVmyRCL5hFHrJInXE6ZSGVIe6