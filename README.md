# robocode_CPS
# Wrecker
Este é um robô desenvolvido para competir em batalhas do Robocode. Utiliza uma combinação de técnicas de evasão, mira e movimentação para vencer os adversários.

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

## Estratégia do Robô
O robô utiliza uma estratégia de:
- **Movimentação**: Evita balas inimigas com movimentação aleatória.
- **Mira**: Utiliza algoritmos de previsão para acertar alvos em movimento.
- **Evasão**: Detecta e evita zonas de alta densidade de fogo.

## Arquitetura do Código
- `NomeDoRobo.java`: Classe principal do robô.
- `Movimentacao.java`: Lógica de movimentação.
- `Mira.java`: Lógica de mira e disparo.
- `Evasao.java`: Lógica de evasão.

## Contribuição
1. Faça um fork deste repositório.
2. Crie uma branch para a sua feature (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`).
4. Push para a branch (`git push origin feature/nova-feature`).
5. Crie um Pull Request.

## Testes
Para rodar testes, utilize a biblioteca [JUnit](https://junit.org/junit5/):
```sh
java -cp libs/robocode.jar:libs/junit5.jar org.junit.platform.console.ConsoleLauncher --scan-classpath
