# Prompt Mestre para Geração de Imagens

Um prompt interativo para transformar uma ideia em uma descrição visual detalhada, pronta para ser usada em um gerador de imagens por IA.

## Como funciona

O assistente conduz a criação do prompt fazendo uma pergunta por vez. Você responde com suas preferências ou pula qualquer item que não se aplique. Ao final, ele reúne as escolhas em um parágrafo detalhado, escrito em inglês, com foco em uma imagem de alta qualidade.

## Exemplos de imagens

Algumas imagens de exemplo geradas com prompts criados a partir deste fluxo:

<table>
	<tr>
		<td align="center" width="25%"><a href="imgs/Gigantic_artisanal_burger_studio…_8b9a5249.jpg"><img src="imgs/Gigantic_artisanal_burger_studio…_8b9a5249.jpg" alt="Hambúrguer artesanal em fotografia de estúdio" width="180"></a><br>Hambúrguer artesanal</td>
		<td align="center" width="25%"><a href="imgs/Gray_alien_staring_into_camera_2d97f906.jpg"><img src="imgs/Gray_alien_staring_into_camera_2d97f906.jpg" alt="Alien em cenário synthwave" width="180"></a><br>Alien synthwave</td>
		<td align="center" width="25%"><a href="imgs/Hyper-realistic,_cinematic_medium_shot_with_dfb93733.jpg"><img src="imgs/Hyper-realistic,_cinematic_medium_shot_with_dfb93733.jpg" alt="Mulher em rua urbana chuvosa" width="180"></a><br>Retrato cinematográfico</td>
		<td align="center" width="25%"><a href="imgs/image.png_87cb1b2f.jpg"><img src="imgs/image.png_87cb1b2f.jpg" alt="Astronauta em campo de girassóis" width="180"></a><br>Astronauta entre girassóis</td>
	</tr>
	<tr>
		<td align="center" width="25%"><a href="imgs/Punk_woman_holding_large_gun_007a1c68.jpg"><img src="imgs/Punk_woman_holding_large_gun_007a1c68.jpg" alt="Mulher punk segurando uma arma de ficção" width="180"></a><br>Personagem punk</td>
		<td align="center" width="25%"><a href="imgs/Sunrise_viewed_from_beach_f0c28de4.jpg"><img src="imgs/Sunrise_viewed_from_beach_f0c28de4.jpg" alt="Praia ao nascer do sol" width="180"></a><br>Amanhecer na praia</td>
		<td align="center" width="25%"><a href="imgs/Woman_pressing_hand_face_89e003c6.jpg"><img src="imgs/Woman_pressing_hand_face_89e003c6.jpg" alt="Mulher pensativa ao entardecer" width="180"></a><br>Retrato emocional</td>
		<td align="center" width="25%"><a href="imgs/Zebra_head_wearing_coat_31e286d6.jpg"><img src="imgs/Zebra_head_wearing_coat_31e286d6.jpg" alt="Zebra usando óculos e casaco" width="180"></a><br>Zebra estilizada</td>
	</tr>
</table>

## O que ele ajuda a definir

- **Tema principal:** o assunto ou a cena que deve aparecer na imagem.
- **Estilo visual:** por exemplo, aquarela, anime, fotorrealismo, arte vetorial, pop art ou xilogravura.
- **Atmosfera:** a sensação transmitida, como aconchegante, misteriosa, épica ou melancólica.
- **Iluminação:** tipo, direção e caráter da luz, como luz natural suave, neon ou luz dramática lateral.
- **Paleta de cores:** combinação e temperatura das cores, como tons pastel, monocromáticos ou cores vibrantes.
- **Composição:** organização dos elementos, enquadramento, perspectiva e profundidade de campo.
- **Tipo de câmera ou lente:** referências de equipamento e perspectiva fotográfica, quando forem relevantes.
- **Detalhes adicionais:** qualquer elemento específico que você queira acrescentar.

As opções sugeridas em cada etapa servem como inspiração; você também pode responder com uma escolha própria.

## Como usar

1. Abra [`prompt_mestre.md`](prompt/prompt_mestre.md) e copie o conteúdo.
2. Cole o texto nas instruções de um assistente de IA capaz de seguir prompts, ou envie-o como a primeira mensagem de uma conversa.
3. Responda às perguntas uma por vez. Para deixar um campo em branco, diga que ele não se aplica ou que deseja pular.
4. Quando o assistente perguntar sobre detalhes adicionais, inclua o que ainda não foi coberto ou indique que não há mais nada.
5. Copie o parágrafo final em inglês e use-o na ferramenta de geração de imagens de sua preferência.

## Dicas

- Descreva o tema principal com elementos concretos, como sujeitos, cenário e ação em detalhes.
- Para ter mais controle, especifique detalhes importantes nas respostas em vez de depender apenas das opções sugeridas.
- Nem toda referência de câmera ou lente é útil para todos os estilos. Pule esse campo quando não fizer sentido para a imagem.
- O resultado é um prompt textual; a geração da imagem acontece em uma ferramenta de imagens separada.

## Arquivo

- [`prompt_mestre.md`](prompt/prompt_mestre.md): prompt completo usado para iniciar o fluxo interativo.