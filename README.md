# Simulação de Planetas em OpenGL

## Disciplina: Computação Gráfica
**Professor:** Marcelo Costa Oliveira

## Descrição
Este projeto utiliza OpenGL para criar uma simulação de dois planetas orbitando ao redor do Sol, com um deles possuindo duas luas com diferentes trajetórias de translação. A animação pode ser iniciada ou pausada pressionando a tecla `Y`.

## Funcionalidades
- O Sol é representado como um círculo amarelo no centro da tela.
- Dois planetas giram ao redor do Sol:
  - O primeiro (azul) gira no sentido horário.
  - O segundo (vermelho) gira no sentido anti-horário.
- O primeiro planeta tem duas luas:
  - Uma gira apenas no eixo X.
  - A outra gira no eixo XY.
- Pressionar a tecla `Y` inicia ou pausa a animação.

## Requisitos
- Python 3.x
- Bibliotecas:
  - `PyOpenGL`
  - `PyOpenGL_accelerate`
  - `freeglut` (caso necessário para execução no Windows/Linux)

## Instalação
1. Instale as dependências com o comando:
   ```bash
   pip install PyOpenGL PyOpenGL_accelerate
   ```
2. Execute o script no VS Code ou outro ambiente Python:
   ```bash
   python nome_do_arquivo.py
   ```

## Controles
- Pressione `Y` para iniciar ou pausar a animação.


