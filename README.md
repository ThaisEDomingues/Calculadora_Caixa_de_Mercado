# Calculadora_Caixa_de_Mercado
Como usar as funções matemáticas da biblioteca numpy e um caixa de mercado que gera cupom fiscal

🧮 Calculadora e Sistema de Caixa com NumPy
Este repositório contém exercícios práticos em Python que demonstram como realizar operações matemáticas de duas formas: utilizando operadores nativos da linguagem e utilizando a biblioteca NumPy. O projeto culmina em um sistema de "Caixa de Supermercado" que processa cupons fiscais.

🚀 Funcionalidades
O código está dividido em três partes principais:

Comparativo Matemático: Demonstração de soma, subtração, multiplicação e divisão usando operadores padrão (+, -, *, /) versus métodos do NumPy (np.add, np.subtract, etc.).

Calculadora Interativa: Um menu utilizando a estrutura while True que permite ao usuário escolher operações aritméticas até decidir sair do programa.

Simulador de Caixa de Supermercado:

Captura nomes, valores e quantidades de produtos.

Armazena os dados em listas dinâmicas utilizando .append().

Utiliza o NumPy para transformar listas em arrays (np.array) e realizar cálculos vetorizados de subtotal (Valor × Quantidade).

Exibe um Cupom Fiscal detalhado utilizando a função zip() para percorrer múltiplas listas simultaneamente.

🧠 Conceitos Aplicados
Bibliotecas Externas: Importação e uso do NumPy com o apelido np.

Estruturas de Repetição: Uso de loops infinitos (while True) com interrupção controlada (break).

Tratamento de Dados: Conversão de strings para float e int.

Manipulação de Strings: Uso do método .lower() para validar entradas de texto (S/N) independentemente da caixa.

Cálculo Vetorizado: Uso do np.multiply() para calcular o total de todos os itens de uma vez, convertendo listas em arrays NumPy.

🛠️ Tecnologias Utilizadas
Python 3

NumPy: Biblioteca para computação científica e manipulação de arrays.

📝 Exemplo de Saída (Cupom Fiscal)
Plaintext
-------CUPOM FISCAL-------
Produto | Valor | Quantidade | Total
agua    -- 2.5   -- 10.0      -- 25.0
leite   -- 5.0   -- 2.0       -- 10.0
📂 Como Executar
Certifique-se de ter o Python instalado.

Instale a biblioteca NumPy via terminal:

Bash
pip install numpy
Execute o script e siga as instruções no console para adicionar produtos ou realizar cálculos.

Este projeto demonstra a transição da lógica de programação básica para o uso de bibliotecas profissionais de processamento de dados.
