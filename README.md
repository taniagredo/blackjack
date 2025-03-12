# 🎲 Blackjack with Dices
An interactive Blackjack game with dice, playable from the terminal. Face off against the CPU and try to reach 21 without going over. The CPU makes strategic decisions based on the selected difficulty level.

**🔗 Access the code: [GitHub - Tania Agredo: Blackjack](https://github.com/taniagredo/blackjack)**

 ## Main Features
- Dice-based Blackjack game.
- Adjustable difficulty levels: Easy, Medium, and Hard.
- Roll the dice to get as close as possible to 21 points.
- Choose whether to risk another roll or stand.
- Interactive terminal interface using @clack/prompts.
- Adaptive CPU intelligence that decides when to roll based on difficulty.
- Dynamic outcomes: win, lose, or tie.

## Preview
1. **Game Start**
   
   ```sh
   ¡Bienvenidos!
   ¿Desea jugar Blackjack?
   1. Sí, en dificultad fácil.
   2. Sí, en dificultad intermedia.
   3. Sí, en dificultad difícil.
   4. No  

3. **First Dice Roll**
   
   ```sh
   🎲 Tiraste los dados: 4, 5, 3 → Total: 12
   🤖 La CPU tiró los dados: 6, 2, 5 → Total: 13
   ¿Desea lanzar el dado de nuevo?
   1. Sí
   2. No

5. **New Roll**
   
   ```sh
   🎲 Lanzaste de nuevo un 6 → Total: 18
   🤖 La CPU lanzó el dado 2 → Total: 15
   ¿Desea lanzar el dado de nuevo?
   1. Sí
   2. No

7. **Final Result**
   
   ```sh
   🎲 Lanzaste de nuevo un 4 → Total: 22
   💀 Has perdido porque te pasaste de 21. CPU ha ganado.

8. **Winning Example**

   ```sh
   🎲 Tiraste los dados: 6, 5, 10 → Total: 21
   🏆 Has ganado. CPU ha perdido.  

9. **Draw Example**

    ```sh
    🎲 Tiraste los dados: 7, 6, 5 → Total: 18
    🤖 La CPU tiró los dados: 6, 6, 6 → Total: 18
    🔄 Es un empate.  

## Prerequisites
Before running the game, make sure you have:
- **Node.js** (recommended version: 16 or higher).
- To check if it's installed, run the following command in your terminal:
  
  ```sh
  node -v

If not installed, download it from [Node.js](https://nodejs.org/)


## Install and Use
1. Clone the repository:
   
   ```sh
   git clone https://github.com/taniagredo/blackjack.git
   cd blackjack
 
3. Install dependencies: 

   ```sh
   npm install @clack/prompts

4. Run the game:

   ```sh
   node blackjack.js

5. Follow the on-screen instructions.

## Build With

- **Node.js** - To run the script in the terminal. 
- **@clack/prompts** - Library for interactive terminal prompts. 
- **JavaScript (ES6+)** - Uses modern features like `async/await`, `reduce()`, `filter()`, etc.

## Contributions
Contributions are welcome! To improve this game:

1. Fork the repository.
2. Create a new branch:

   ```sh
   git checkout -b feature-nueva-funcionalidad
   
3. Make your changes and commit them:
   ```sh
   git commit -m "Descripción del cambio"
   git push origin feature-nueva-funcionalidad

4. Submit a Pull Request.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
