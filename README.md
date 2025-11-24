🎲 Corrida Estatística
Uma experiência interativa que combina jogos de tabuleiro com análise estatística em tempo real


📋 Sobre o Projeto
Corrida Estatística é um jogo educativo desenvolvido em Python que transforma conceitos complexos de probabilidade e estatística em uma experiência lúdi
ca e visual. Dois jogadores competem em um tabuleiro dinâmico enquanto o sistema gera gráficos em tempo real mostrando distribuições probabilísticas e a convergência das médias.

✨ Características Principais
🎮 Jogo Interativo
Tabuleiro Zig-Zag: Layout único com 30 casas

Casas Especiais: Casas de Sorte (+1 a +4) e Azar (-1 a -4)

Sistema de Poderes: 4 poderes especiais por jogador

Multiplayer: Dois jogadores com cores distintas

📊 Análise Estatística em Tempo Real
Gráfico de Distribuição: Mostra frequências relativas vs distribuição teórica

Lei dos Grandes Números: Gráfico de convergência da média acumulada

Eixo X Dinâmico: Ajusta automaticamente para valores acima de 12

Estatísticas Descritivas: Média, mediana e moda atualizadas

🎯 Poderes Especiais
🎲 Dobrar Dados - Próximo lançamento é multiplicado por 2

🔙 Retroceder Oponente - Oponente volta 3 casas

🔄 Trocar Posições - Troca de lugar com o oponente

🔄 Jogar Novamente - Joga os dados novamente no mesmo turno

🛠️ Tecnologias Utilizadas
Python 3.8+ - Linguagem principal

Pygame - Renderização gráfica e interface

Matplotlib - Geração de gráficos estatísticos

NumPy - Cálculos estatísticos e matemáticos

Random - Geração de números aleatórios para os dados

🚀 Como Executar
Pré-requisitos
Python 3.8 ou superior

Pip (gerenciador de pacotes Python)

Instalação
Clone o repositório:

bash
git clone https://github.com/sam-abreu/corrida-estatistica.git
cd corrida-estatistica
Instale as dependências:

bash
pip install pygame matplotlib numpy
Execute o jogo:

bash
python corrida_estatistica.py
🎮 Controles
Espaço: Jogar dados

R: Reiniciar jogo

ESC: Sair do jogo

Mouse: Navegação nos menus e botões

📈 Conceitos Estatísticos Ensinados
1. Distribuição de Probabilidade
Probabilidade teórica vs frequência empírica

Distribuição da soma de dois dados (triangular)

Lei dos Grandes Números na prática

2. Estatísticas Descritivas
Média Aritmética: Tendência central dos lançamentos

Mediana: Valor central da distribuição

Moda: Valor mais frequente nos lançamentos

3. Convergência Estatística
Visualização da Lei dos Grandes Números

Estabilização da média com mais observações

Comparação com valor teórico esperado (7.0)

🎯 Regras do Jogo
Objetivo
Ser o primeiro jogador a chegar à casa 30 (META)

Mecânicas Principais
Turnos Alternados: Cada jogador lança dois dados por vez

Movimento: Soma dos valores dos dados determina casas avançadas

Casas Especiais:

🍀 Sorte: Avança casas extras (1-4)

⚠️ Azar: Retrocede casas (1-4)

Poderes: Cada jogador tem um poder único por partida

Casas Especiais
Casa	Tipo	Efeito	Descrição
3	🍀 Sorte	+2	Atalho!
8	🍀 Sorte	+3	Vento!
12	🍀 Sorte	+1	Passo!
18	🍀 Sorte	+2	Escada!
22	🍀 Sorte	+4	Jato!
28	🍀 Sorte	+1	Quase!
4	⚠️ Azar	-2	Queda!
7	⚠️ Azar	-3	Buraco!
11	⚠️ Azar	-1	Ops!
14	⚠️ Azar	-2	Volta!
17	⚠️ Azar	-4	Crise!
21	⚠️ Azar	-2	Recuo!
26	⚠️ Azar	-3	Monstro!
