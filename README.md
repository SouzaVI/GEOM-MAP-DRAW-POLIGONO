


## Mapa Interativo para Localização e delimitação de áreas
Módulo de mapa interativo! Este componente, desenvolvido em Flask e Folium, proporciona uma aplicação web para visualização de mapas e delimitação de áreas.
## Contextualização

### Sobre o Módulo
Este módulo é parte integrante de um projeto maior, dedicado a facilitar a interação com mapas. Desenvolvido em Flask e integrando o Folium, ele proporciona uma experiência prática na visualização e manipulação de dados geoespaciais.


## Funcionalidades Principais
1. **Mapa Interativo:** Utiliza o framework Flask para criar uma aplicação web com um mapa dinâmico, facilitando a visualização de áreas agrícolas.

2. **Integração com Folium:** A biblioteca Folium desempenha um papel crucial no projeto, permitindo a criação fácil de mapas interativos e a manipulação eficiente de dados geoespaciais.

3. **Desenho de Áreas:** Os usuários podem desenhar áreas diretamente no mapa, fornecendo uma maneira intuitiva de delimitar talhões agrícolas.

4. **Buscar cidade:**:  Os usuários podem pesquisar cidade de interesse, dessa forma, centralizando mapa na cidade escolhida.

## Configuração e Uso

### Requisitos
Certifique-se de ter Python instalado em sua máquina. Instale as dependências necessárias executando o seguinte comando:
```bash
pip install flask folium
```

### Executando a Aplicação
Para iniciar o servidor Flask, utilize o seguinte comando:
```bash
python app.py
```
Acesse a aplicação em seu navegador, geralmente em [http://localhost:5000](http://localhost:5000).

## Entendendo o Código
O arquivo `app.py` contém a lógica principal do aplicativo. Aqui estão algumas explicações importantes:

- **Rota `/`:** Esta rota renderiza a página inicial, que pode ser personalizada no arquivo `index.html` localizado na pasta `templates`.
## Demonstração
https://github.com/SouzaVI/GEOM-MAP-DRAW-POLIGONO/assets/98165012/da48de9b-c7d4-4653-ac59-5d0550681a22
