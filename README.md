## Website Performance Optimization portfolio project

### Como subir o projeto utilizando python e ngrok

1. Rodar o python para servir o conteudo:

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```

1. Download e instale [ngrok](https://ngrok.com/) na raíz do projeto.

  ``` bash
  $> cd /path/to/your-project-folder
  $> ./ngrok http 8080
  ```

1. A url gerada pelo ngrok é publica e pode ser usada para medir o desempenho do site.


####Part 2: Otimizações realizadas no projeto para atingir niveis aceitaveis de performance:

1. index.html


