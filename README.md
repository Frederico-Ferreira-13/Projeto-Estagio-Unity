# Projeto-Estagio-UniJogo: Classificação de Cores
Benefícios Cognitivos
Este jogo desenvolve o Raciocínio Lógico através da Classificação. A criança aprenderá a identificar que objetos diferentes (com diferentes formas, tamanhos, ou categorias) podem ser agrupados sob uma característica comum (cor), ignorando outros atributos. Este treino promove a aquisição de conceitos abstratos, ensinando a procurar a característica essencial para agrupar.
Instruções
1.	Objetivo: Classificar corretamente 10 objetos coloridos nas caixas correspondentes no menor tempo possível.
2.	Mecânica: Use o rato (ou toque) para arrastar e largar o objeto colorido sobre a caixa que tem a mesma cor (Vermelho, Azul, Verde ou Amarelo).
3.	Feedback Positivo (Sucesso): O objeto desaparece, é contabilizado um ponto, e um novo objeto aparece no local de spawn.
4.	Feedback Negativo (Erro): Se o objeto for colocado na caixa errada, a caixa piscará brevemente, e o objeto regressará à sua posição inicial para que possa ser reclassificado. É aplicada uma penalização de tempo (se configurada).
Níveis de Dificuldade Sugeridos
A dificuldade pode ser ajustada nas configurações do GameManager.cs e através dos prefabs dos objetos:
Nível 1: Introdução (Fácil)
•	Ajuste do Jogo: Usar objetos com cores puras e óbvias (ex: um quadrado vermelho, um círculo azul).
•	Variáveis (GameManager):
o	timeLimit: Mais longo (ex: 90 segundos).
o	incorrectClassificationPenalty: 0f (Sem penalização de tempo para evitar frustração inicial).
o	itemsToClassify: 5 objetos.
Nível 2: Prática (Médio)
•	Ajuste do Jogo: Usar objetos com imagens reais (ex: morango, banana, carro azul, folha verde) onde a cor é predominante, mas o objeto tem forma e textura.
ty
