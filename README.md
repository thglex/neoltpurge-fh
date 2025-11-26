# NeoLT Purge FH

Ferramenta profissional para limpeza automática de ONUs offline em OLTs Fiberhome.

##  Características Principais

-  **Identificação automática** de ONUs offline há mais de 90 dias
-  **Remoção em lote** com confirmação de segurança
-  **Interface segura** com entrada de senha oculta
-  **Log detalhado** de todas as operações
-  **Suporte multiplataforma** (Linux e Windows)
-  **Barra de progresso** em tempo real
-  **Múltiplas PONs** suportadas simultaneamente

##  Download

**Versão Atual:** v1.15.0

### Binários Disponíveis:
- `neoltpurge-fh-linux` - Para sistemas Linux (64-bit)
- `neoltpurge-fh-windows.exe` - Para Windows (64-bit)

##  Instalação Rápida

### Linux:
```bash
# Download do binário
wget https://github.com/thglex/neoltpurge-fh/releases/download/v1.15.0/neoltpurge-fh-linux

# Tornar executável
chmod +x neoltpurge-fh-linux

# Executar
./neoltpurge-fh-linux --help
