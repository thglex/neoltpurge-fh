# Changelog - NeoLT Purge FH

Todos os cambios notáveis neste projeto serão documentados neste arquivo.

## [1.177777772025-11-26
### Added
- 🎉 **Lançamento Inicial**
- Funcionalidade completa de limpeza de ONUs offline
- Sistema de log avançado com timestamps
- Interface de linha de comando profissional
- Suporte a parâmetros nomeados
- Entrada segura de senha com ocultação
- Barra de progresso em tempo real
- Verificação pós-remoção
- Suporte a múltiplas PONs simultâneas
- Detecção automática de portas PON
- Configuração de log personalizável

### Features
- **Listagem inteligente**: Identifica ONUs offline >90 dias ou com LASTOFFTIME = "--"
- **Remoção segura**: Confirmação antes de cada operação em lote
- **Log detalhado**: Registro completo em `~/.neoltpurge-fh/logs/`
- **Multiplataforma**: Compatível com Linux e Windows
- **Flexível**: Suporte a UNM/OLT personalizados

### Technical
- Código otimizado e independente
- Tratamento robusto de erros
- Conexões TL1 gerenciadas adequadamente
- Arquitetura modular e maintainable

## Próximas Versões
### Planned
- [ ] Interface web opcional
- [ ] Agendamento de tarefas
- [ ] Relatórios em PDF
- [ ] Suporte a múltiplos OLTs simultâneos
- [ ] API REST
- [ ] Dashboard web

---
*O formato deste changelog é baseado em [Keep a Changelog](https://keepachangelog.com/pt-BR/1.0.0/)*
