# 📋 Sistema Interno de Registro de Atendimentos e Base de Conhecimento

Projeto voltado à organização de chamados por categoria e prioridade, análise de tempo de resposta e documentação de guias passo a passo para incidentes frequentes.

## 🎯 Funcionalidades
- Registo estruturado de chamados com **categoria**, **prioridade** e **tempo de resposta**.
- Geração de resumo analítico (`resumo_chamados.txt`) para acompanhar volume e tempo médio de resposta.
- **Base de conhecimento** (`base_de_conhecimento.md`) com passo a passo para incidentes comuns de suporte.

## 📂 Estrutura do Projeto
- `gestao_chamados.py`: Script principal de registo, listagem e resumo de chamados.
- `base_de_conhecimento.md`: Guias de resolução rápida para incidentes frequentes.
- `chamados.json`: Base local de chamados (criada automaticamente).
- `resumo_chamados.txt`: Relatório analítico gerado pela opção 3 do menu.

## ▶️ Como Executar
```bash
python3 gestao_chamados.py# sistema-chamados-base-conhecimento
