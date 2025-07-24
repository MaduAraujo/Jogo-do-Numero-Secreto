# Jogo do Número Secreto

## Sobre o Projeto

Este é um jogo de adivinhação simples e interativo, desenvolvido com **HTML, CSS e JavaScript**. 
O objetivo é que o usuário adivinhe um número secreto gerado aleatoriamente entre 1 e 10. O jogo oferece feedback claro sobre se o chute foi muito alto ou muito baixo, 
guiando o jogador até a resposta correta. Para tornar a experiência ainda mais envolvente e acessível, ele integra a biblioteca `responsivevoice.js` para fornecer feedback 
de áudio, lendo as mensagens do jogo em voz alta.

## Funcionalidades

  * **Adivinhação de Número Secreto:** O jogo gera um número secreto aleatório entre 1 e 10 para o jogador adivinhar.
  * **Feedback Interativo:** O jogador recebe mensagens instantâneas indicando se o chute foi **maior** ou **menor** que o número secreto.
  * **Contador de Tentativas:** O jogo registra e exibe o número de tentativas que o jogador levou para acertar o número.
  * **Novo Jogo:** Um botão "Novo jogo" é ativado após o jogador acertar, permitindo reiniciar o jogo com um novo número secreto.
  * **Limpeza Automática do Campo:** O campo de entrada é limpo após cada chute para facilitar a próxima tentativa.
  * **Números Não Repetidos:** O jogo garante que o número secreto não se repita até que todos os números possíveis (de 1 a 10) tenham sido sorteados, garantindo uma experiência variada.
  * **Feedback por Voz:** Utiliza a biblioteca `responsivevoice.js` para ler as mensagens do jogo em português brasileiro (voz feminina), aprimorando a experiência do usuário.

## Tecnologias Utilizadas

  * **HTML5:** Estrutura da página web.
  * **CSS3:** Estilização e design da interface do usuário.
  * **JavaScript:** Toda a lógica do jogo.
  * **ResponsiveVoice.js:** Biblioteca externa para síntese de fala (text-to-speech).

## Como Rodar o Projeto

Para executar este projeto localmente no seu computador, siga os passos abaixo:

1.  **Clone o repositório**:

    ```bash
    git clone https://github.com/MaduAraujo/Jogo-do-Numero-Secreto
    ```
    Ou baixe o arquivo ZIP do projeto.

2.  **Navegue até o diretório do projeto**:

    ```bash
    cd Jogo-do-Numero-Secreto
    ```

3.  **Abra o arquivo `index.html`** no seu navegador web e interaja com o jogo.
