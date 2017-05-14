## Website Performance Optimization

### Como subir o projeto utilizando python e ngrok

1. Rodar o python para servir o conteudo:

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```

2. Download e instale [ngrok](https://ngrok.com/) na raíz do projeto.

  ``` bash
  $> cd /path/to/your-project-folder
  $> ./ngrok http 8080
  ```

3. A url gerada pelo ngrok é publica e pode ser usada para medir o desempenho do site.


#### Otimizações realizadas no projeto para atingir niveis aceitaveis de performance:

**1. index.html**:
 * Mover o style.css para o index.html
 * Carregar o print.css somente quando para impressão adicionando *media="print"*
 * *async* adicionado para carregar assincronamente os js perfmatters.js e analytics.js
 * arquivo perfmatters.js minificado

**2. pizza.html**:
 * Mover o style.css para o pizza.html


