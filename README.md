# Protótipo de Alta Fidelidade — TAR-06 (DF no Ponto)

Protótipo navegável usado na avaliação de alta fidelidade da **TAR-06 — Consulta de ônibus em tempo real no DF no Ponto**, do projeto do Grupo 05 da disciplina Interação Humano-Computador (FCTE/UnB, 2026/2).

- **Abrir:** https://carloshfgit.github.io/prototipo-tar06-df-no-ponto/
- **Projeto do grupo:** https://interacao-humano-computador.github.io/2026.2-Grupo05/
- **Autor do design:** [Carlos Costa](https://github.com/carloshfgit)

Os dados (linhas 2310, 2301, 2302 e 2130, pontos e horários) são **fictícios**. O protótipo não consulta nenhum serviço real.

## Como usar nas sessões

1. Abra o link no navegador do celular e use "Adicionar à tela inicial" para abrir em tela cheia.
2. **Painel do condutor:** segure 3 s na faixa azul do topo da tela inicial, ou abra o link com `#condutor`. Ele permite:
   - iniciar uma nova sessão (zera favoritos, avisos, buscas e registro);
   - mostrar o aviso de posição desatualizada na hora;
   - mudar o tempo até o aviso aparecer (padrão: 20 s após abrir a linha 2310);
   - exportar o registro de toques e telas.
3. Sem internet, o arquivo `index.html` salvo no aparelho também funciona (só a fonte muda).

## Telas

| ID | Tela |
| :---: | :--- |
| A1 | Início (busca, linhas favoritas e mapa) |
| A2 | Busca com sugestões e mensagem de busca sem resultado |
| A3 | Resultados por lugar ou por ponto |
| A4 | Linha: previsão, última atualização, favoritar, avisar atraso e viagem |
| N1 | Aviso de posição desatualizada ("Consultar de novo" e "Ver alternativas") |
| A5 | Alternativas |
| N2 | Confirmações de favorito e de aviso de atraso |
| A6 | Favoritos |

Capturas de cada tela estão em [`capturas/`](capturas/).

## Declaração sobre o uso de IA generativa

O código foi implementado com o **Claude Code (Anthropic)** a partir das telas, dos textos, dos dados fictícios e das decisões de design definidos pelo autor, que revisou e testou cada tela no celular.
