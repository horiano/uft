# Criação de um pacote uft.sty

Este projeto é para criação de um pacote baseado no abntex2, segundo o [MANUAL DE NORMALIZAÇÃO PARA ELABORAÇÃO DE TRABALHOS ACADÊMICO–CIENTÍFICOS DAUNIVERSIDADE FEDERAL DO TOCANTINS](http://www.uft.edu.br/producaovegetal/doc/Normalizacao-Elaboracao-Trabalhos-UFT.pdf).

## Requisitos

É preciso usar a classe abntex2. É necessário que o arquivo uft.sty e logouft.pdf estejam na mesma pasta do seu documento latex principal.

Exemplo simples:
 
```
\documentclass[12pt,a4paper,brazil]{abntex2}

%outros pacotes aqui

\usepackage{uft}

%outras opcções

\begin{document}

% Conteúdo

\end{document}
```

## Comandos disponiveis

Dois comandos estão disponíveis, para que as capas sejam alterados de acordo com o curso e o campus. Eles são:

* \curso{Nome do curso}
* \campus{Nome de campus}

Eles devem ser usados antes do comando \begin{document}.
