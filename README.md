# Wrecker
Este é um robô desenvolvido para competir em batalhas do Robocode. Utiliza uma combinação de técnicas de evasão, mira e movimentação para vencer os adversários.

### Wrecker em batalha
<details>
  <summary>📸</summary>
  Wrecker é o robo branco e vermelho
  <img src="wrecker.gif" alt="Screen" style="width: 70%; max-width: 200px;">
  
</details>


## Pré-requisitos
- Java 8 ou superior
- Robocode 1.9.3.0 ou superior

## Instalação
1. Baixe e instale o [Robocode](https://robocode.sourceforge.io/).
2. Clone este repositório:
    ```sh
    git clone (https://github.com/joaocarpim/robocode_CPS.git)
    ```
3. Importe o projeto no seu IDE de preferência (Robocode).

## Como Usar
1. Compile o robô:
    ```sh
    javac -cp libs/robocode.jar src/seu/pacote/*.java
    ```
2. Execute o Robocode e importe o robô compilado.
3. Selecione o robô e inicie uma batalha.

## Contribuição
1. Faça um fork deste repositório.
2. Crie uma branch para a sua feature (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`).
4. Push para a branch (`git push origin feature/nova-feature`).
5. Crie um Pull Request.

## Resumo do Wrecker
O robô Wrecker é projetado para competições de Robocode, destacando-se por sua movimentação circular contínua para evitar previsibilidade e sua capacidade de ajustar dinamicamente velocidade e potência de tiro com base na distância do inimigo.
Utiliza mira precisa e responde defensivamente a colisões, além de celebrar vitórias.

## Testes
Para rodar testes, utilize a biblioteca [JUnit](https://junit.org/junit5/):

      ```sh    
     java -cp libs/robocode.jar:libs/junit5.jar org.junit.platform.console.ConsoleLauncher --scan-classpath
    
## Equipe

Desenvolvedores da lógica embutida à inteligência do robô wrecker:
- [João Carpim](https://github.com/joaocarpim)
- [José Lisboa](https://github.com/proceed15)
- [Luis Gabriel](https://github.com/luisgabriel)

