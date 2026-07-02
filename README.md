#  Sistema de Notas para Competições (Skate/Surf)

Este projeto simula o sistema oficial de pontuação utilizado em campeonatos de esportes de ação. O programa coleta as notas dos juízes, valida as entradas e calcula a média final descartando os extremos.

##  Funcionalidades
* **Validação de Dados:** Utiliza um laço `while True` com `break` para garantir que o sistema só aceite notas válidas (entre 0 e 10), impedindo erros de digitação.
* **Critério de Desempate/Regra Oficial:** Identifica e remove automaticamente a maior e a menor nota da lista antes de calcular a média.
* **Formatação Precisa:** Exibe o resultado final elegantemente formatado com duas casas decimais.

## 🛠️ Tecnologias Utilizadas
* **Python 3** (Lógica de listas, controle de fluxo e funções nativas como `max()`, `min()`, `sum()` e `len()`).

##  Como Executar o Projeto
1. Certifique-se de ter o Python instalado na sua máquina.
2. Baixe o arquivo `main.py`.
3. Rode o comando no seu terminal:
   ```bash
   python main.py
