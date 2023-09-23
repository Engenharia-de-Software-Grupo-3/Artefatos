Algumas considerações para a equipe de implementação:

- SPRITES: Os sprites dos personagens podem ser invertidos, de acordo com a posição em que eles se encontram. Prefiro que não invertam os sprites de Prolog e de Haskell, mas se não for possível evitar, então tudo bem.

- PNGS DA BATALHA: Os pngs foram feitos com a ideia de três estados (parado, atacando e tomando dano). Os sprites 1 e 2 de cada personagem referem-se aos dois primeiros estados. Para o terceiro estado, a ideia é que:
	> em Python e Lua, o sprite 1 e o sprite 3 piscam
	> em Java e Ruby, os sprites 3 e 4 piscam, para dar o efeito de dano que vocês já devem ter visto em vários jogos. Se não for possível fazer os sprites "piscarem", então usem a versão vermelha.
	> Os inimigos possuem 2 sprites com o estado de "parado". A ideia é que eles alternem para dar uma ideia de animação. Se isso não for possível, usem o sprite com a indicação "parado 1" para esse estado.
