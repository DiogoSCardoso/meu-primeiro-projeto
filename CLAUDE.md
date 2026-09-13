# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## O que é esta pasta

`treino-claude` não é um projeto de software — é uma área pessoal de prática usada para aprender a usar o Claude Code (ver `objetivos.md` e `agenda.md`). Há um repositório git local (sem remoto configurado), mas não há gerenciador de pacotes, build, lint ou suíte de testes. Trate arquivos aqui como material de exercício e conteúdo pessoal (CV, notas, planilhas), não como um codebase de produção.

## Ambiente Python

O Python não está no PATH deste ambiente de shell. Use o caminho completo do interpretador ao rodar scripts:

```
"C:\Users\diogo\AppData\Local\Programs\Python\Python312\python.exe" scripts\nome_do_script.py
```

Bibliotecas de terceiros usadas nos scripts existentes (instaladas globalmente, sem venv):
- `openpyxl` — geração de planilhas `.xlsx` (usado em `gerar_planilha.py`)

## Estrutura de pastas

Os arquivos estão organizados por tipo em subpastas. `CLAUDE.md`, `agenda.md` e `objetivos.md` ficam na raiz.

- `scripts/` — os dois scripts `.py`.
- `planilhas/` — planilhas `.xlsx` geradas (ex: `meses.xlsx`).
- `notas/` — notas mensais `.txt`.
- `documentos/` — outros documentos (ex: CV em `.pdf`).

## Scripts existentes

- `scripts/contar_extensoes.py` — conta, recursivamente, todos os arquivos da pasta `treino-claude` (incluindo subpastas) agrupados por extensão.
- `scripts/gerar_planilha.py` — gera `planilhas/meses.xlsx` com os meses de janeiro a maio e um valor aleatório por linha.

## Fluxo de trabalho com git

Sempre que uma tarefa for concluída, faça um commit com mensagem descritiva em português resumindo o que foi feito.
