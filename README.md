# Atividade 1 - Algoritmos e Programação II

**Nome:**  
**RA:**  

---

## Descrição da Atividade

Nesta atividade, o desafio é **analisar os códigos-fonte dos Exercícios 1 a 5**, identificar os **defeitos lógicos** existentes e realizar as correções necessárias.  

As correções devem ser entregues via **commit/push** das alterações no repositório.  

⚠️ **Atenção:**  
Caso você substitua o código inteiro por um novo sem preservar a estrutura fornecida, isso será detectado no commit e **a nota não será contabilizada**.

📅 **Prazo para efetuar o commit:** 01/10  

📊 **Pontuação:**  
Cada exercício corrigido vale **2,0 pontos**, totalizando 10,0 pontos.

---

## Comportamento Esperado dos Exercícios

### Exercício 1 — Verificação de Número Positivo, Negativo ou Zero
O programa deve ler um número digitado pelo usuário e verificar corretamente se ele é **positivo**, **negativo** ou **igual a zero**.  
- Caso seja maior que zero, deve exibir uma mensagem indicando que o número é positivo.  
- Caso seja menor que zero, deve indicar que é negativo.  
- Caso seja igual a zero, deve informar que é zero.  

Assim, o programa ajuda o usuário a identificar corretamente a natureza do número inserido, utilizando de forma coerente as estruturas condicionais.

---

### Exercício 2 — Detecção de Número Primo
O programa deve detectar se um número é primo ou não.  
Um **número primo** é um inteiro maior que 1 que possui **exatamente dois divisores distintos**: 1 e ele próprio.  
Isso significa que ele não pode ser decomposto em fatores menores além desses dois divisores.  
Exemplos: **2, 3, 5, 7, 11** são primos, enquanto **4, 6, 8, 9** não são, pois possuem outros divisores além de 1 e de si mesmos.

---

### Exercício 3 — Operações com Vetores
O programa deve:  
1. Solicitar ao usuário quantos números deseja digitar (entre 1 e 100).  
2. Ler esses números e armazená-los em um vetor.  
3. Calcular a soma de todos os elementos.  
4. Determinar o **maior valor** presente no vetor (mesmo que todos sejam negativos).  
5. Calcular a **média aritmética** usando ponto flutuante para evitar perda de precisão.  
6. Exibir na tela a média e o maior valor encontrado.  

O programa deve produzir resultados corretos independentemente da combinação de números inseridos.

---

### Exercício 4 — Cálculo de Área de Triângulo com Matrizes
O programa deve:  
1. Ler as coordenadas de três pontos no plano cartesiano.  
2. Armazenar cada par `(x, y)` em uma matriz 3x3, onde a terceira coluna seja composta por valores iguais a 1.  
3. Calcular corretamente o **determinante** dessa matriz usando a regra de Sarrus ou expansão por cofatores (respeitando os sinais alternados + - +).  
4. Dividir o valor absoluto do determinante por 2.0 para obter a **área exata** do triângulo.  
5. Utilizar variáveis `float` ou `double` para permitir cálculos com ponto flutuante.  
6. Exibir a área calculada de forma precisa, independentemente da posição ou orientação dos pontos.

---

### Exercício 5 — Troca de Valores Usando Ponteiros
O programa deve:  
1. Ler dois valores inteiros.  
2. Criar ponteiros para essas variáveis.  
3. **Trocar corretamente** os valores de forma que `x` receba o valor original de `y` e `y` receba o valor original de `x`.  
4. Exibir os valores antes e depois da troca para comprovar o resultado.
