# Formação em Kotlin

Este projeto é um programa em Kotlin que simula um sistema de matrícula e gerenciamento de conteúdos para diferentes formações acadêmicas.

## Como executar

Para executar este projeto, você precisa ter o Kotlin instalado na sua máquina. Você pode seguir as instruções de instalação no site oficial do Kotlin: [https://kotlinlang.org/docs/command-line.html].

Depois de instalar o Kotlin, você pode clonar este repositório e navegar até a pasta do projeto. Em seguida, você pode compilar e executar o arquivo `main.kt` com os seguintes comandos:


kotlinc main.kt -include-runtime -d main.jar java -jar main.jar


## Funcionalidades

Este projeto possui as seguintes funcionalidades:

- Criar diferentes formações com uma lista de conteúdos, cada um com um nome, uma duração e um nível de dificuldade.
- Criar diferentes usuários com um nome.
- Matricular um usuário em uma formação, verificando se ele já está matriculado ou não.
- Imprimir as matérias de cada formação, mostrando o nome, o nível e a duração de cada conteúdo.

## Exemplo de saída

A saída esperada do programa é algo como:


Matrícula realizada, para Rayanne na formação Design de Moda. Matrícula realizada, para Osmar na formação Engenharia Mecatrônica. Matrícula realizada, para Arthur na formação Astronomia.

Matérias da formação Design de Moda: Desenho de Moda - Nível: BASICO Processo Criativo - Nível: INTERMEDIARIO Linguagem Visual - Nível: AVANÇADO

Matérias da formação Engenharia Mecatrônica: Cálculo Diferencial e Integral I - Nível: BASICO Geometria Analítica e Álgebra Linear - Nível: INTERMEDIARIO Sistemas Hidráulicos E Pneumáticos - Nível: AVANÇADO

Matérias da formação Astronomia: Programa Espacial Brasileiro - Nível: BASICO Diagrama H-R e Evolução Estelar - Nível: INTERMEDIARIO Estrelas Binárias e Variáveis - Nível: AVANÇADO
