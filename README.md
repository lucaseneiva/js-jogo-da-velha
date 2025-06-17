
# ❌⭕ Jogo da Velha

![Licença](https://img.shields.io/badge/licença-Não--especificada-lightgrey)

Uma implementação clássica do Jogo da Velha (Tic-Tac-Toe) construída inteiramente com HTML, CSS e JavaScript puro. O projeto foca em uma lógica de jogo limpa e em uma interface minimalista, utilizando técnicas modernas de CSS para renderizar os elementos do jogo.

## 📸 Demonstração

![Animação](https://github.com/user-attachments/assets/41ca4e7a-4bde-4502-8fff-f9dd5f6b6ccb)

## ✨ Funcionalidades

- **Jogabilidade Clássica:** Jogue contra um amigo localmente, alternando entre 'X' e 'O'.
- **Detecção de Vencedor e Empate:** O jogo identifica automaticamente todas as condições de vitória (linhas, colunas e diagonais) e também os empates.
- **Feedback Visual Dinâmico:** O tabuleiro mostra um "fantasma" do 'X' ou 'O' na célula em que o mouse está, indicando a jogada do jogador atual.
- **Mensagem de Fim de Jogo:** Uma sobreposição clara informa quem venceu ou se o jogo empatou.
- **Botão de Reiniciar:** Comece uma nova partida a qualquer momento com um único clique.

## 🧠 Destaques do Código

Este projeto utiliza algumas abordagens interessantes:

- **Marcadores com CSS Puro:** Os símbolos 'X' e 'O' não são imagens ou caracteres de texto, mas sim desenhados com os pseudo-elementos `::before` e `::after` do CSS, tornando o carregamento instantâneo e o design flexível.
- **Lógica de Jogo Eficiente:** A verificação de vitória é feita de forma declarativa, comparando o estado do tabuleiro com um array de combinações vencedoras (`WINNING_COMBINATIONS`).
- **Gerenciamento de Estado com Classes:** O estado do jogo (de quem é a vez, células preenchidas) é gerenciado principalmente através da adição e remoção de classes CSS no DOM, mantendo o JavaScript focado na lógica.

## 🚀 Tecnologias Utilizadas

- **HTML5:** Estrutura semântica do tabuleiro e dos elementos da interface.
- **CSS3:** Estilização completa, incluindo o uso de **CSS Grid Layout** para o tabuleiro e pseudo-elementos para os marcadores.
- **JavaScript (ES6):** Toda a lógica do jogo, manipulação de eventos e atualização do DOM.

## 🏁 Como Executar

Este é um projeto puramente front-end. Para executá-lo, siga estes passos:

1.  **Clone este repositório:**
    ```bash
    git clone https://github.com/lucasneiva/js-jogo-da-velha.git
    ```

2.  **Navegue até a pasta do projeto:**
    ```bash
    cd js-jogo-da-velha
    ```

3.  **Abra o arquivo `index.html` em seu navegador de preferência.**
    - Você pode simplesmente dar um duplo clique no arquivo ou arrastá-lo para a janela do navegador.

Pronto! O jogo estará funcionando e pronto para jogar.

## 📝 Licença

Este projeto não possui uma licença definida. Sinta-se à vontade para adicionar uma, como a [MIT License](https://choosealicense.com/licenses/mit/).

---

Criado por **Lucas Neiva**.
