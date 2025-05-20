# SmkProject1 - Calculadora no Termux

Projeto feito em Python para rodar no Termux com uma interface simples, bonita e interativa.

## Funcionalidades

- Interface colorida e com menu
- Título "Feito por Smk" em roxo
- Menu com 4 opções:
  - Fazer cálculos (+, -, x, ÷, ^, √)
  - Tutorial explicando com exemplos
  - Redes sociais (Instagram, YouTube, Discord)
  - Sair
- Suporta espaços ou sem espaços nos cálculos
- Atalho de execução simples: `calcsmk`

## Instalação

No Termux:

```bash
pkg update && pkg upgrade -y
pkg install git python -y
git clone https://github.com/SeuUsuario/SmkProject1.git
cd SmkProject1
chmod +x instalar_calcsmk.sh
./instalar_calcsmk.sh
