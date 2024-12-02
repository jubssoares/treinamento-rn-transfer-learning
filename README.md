<h1>Treinamento de Redes Neurais com Transfer Learning</h1>

<img align="right" height="200" style="border-radius:50px;" src="https://assets.dio.me/kCPUcBRKwIhY3--gHdSspiZWdpUXMS2UD0wXM7klMb4/f:webp/h:120/q:80/L3RyYWNrcy81NzQ0ODVlZS0xZTk1LTQzMjAtOThlYy1kMTUyZGQ4ZDk5YmQucG5n">

<h3>Repositório criado para o desafio do bootcamp BairesDev - Machine Learning Practitioner</h3>

<h3>Classificação de Imagens de Gatos e Cachorros 🐱🐶</h3>

<p  align="justify">
    Este projeto utiliza uma rede neural convolucional (CNN) desenvolvida em TensorFlow/Keras para classificar imagens de gatos e cachorros. A base de dados utilizada é o conjunto Cats and Dogs disponibilizado pela Microsoft.
</p>


<h2>🚀 Tecnologias Utilizadas</h2>

<ul>
    <li><b>Python:</b> Linguagem de programação principal.
    <li><b>TensorFlow/Keras:</b> Framework para construção e treinamento da CNN.
    <li><b>Pillow:</b> Biblioteca para manipulação de imagens.
    <li><b>Matplotlib:</b> Visualização de gráficos e resultados.
    <li><b>ImageDataGenerator:</b> Ferramenta para pré-processamento e augmentação de imagens.
</ul>



<h2>📂 Estrutura do Projeto</h2>

```plaintext
├── dataset/
│   └── cats_and_dogs.zip      # Arquivo compactado com o dataset
├── cats_and_dogs/
│   └── PetImages/             # Diretório extraído contendo as imagens
├── model_training.py          # Script principal com o código do projeto
├── README.md                  # Arquivo com informações do projeto

```

<h2>🛠️ Etapas do Projeto</h2>

<div align="justify">
    <ol>
        <b><li>Preparação do Ambiente</li></b>
            <ul>
                <li>Importação das bibliotecas.
                <li>Extração do dataset compactado.
            </ul>
        <b><li>Tratamento de Dados</li></b>
            <ul>
                <li>Remoção de imagens corrompidas utilizando <code>Pillow</code>.
                <li>Pré-processamento e divisão dos dados (treinamento e validação) com <code>ImageDataGenerator</code>.
            </ul>
        <b><li>Definição do Modelo</li></b>
            <ul>
                <li>Construção de uma rede neural convolucional (CNN) com arquitetura:
                    <ul>
                        <li>Camadas de convolução (Conv2D).
                        <li>Camadas de pooling (MaxPooling2D).
                        <li>Camadas densas totalmente conectadas.
                    </ul>
                <li>Compilação do modelo com função de perda binária (<code>binary_crossentropy</code>) e otimizador <code>Adam</code>.
            </ul>
        <b><li>Treinamento do Modelo</li></b>
            <ul>
                <li>Treinamento do modelo com 10 épocas utilizando os dados pré-processados.
                <li>Validação durante o treinamento.
            </ul>    
        <b><li>Visualização dos Resultados</li></b>
            <ul>
                <li>Geração de gráficos para acompanhar a precisão e a perda durante o treinamento.
            </ul>
</ol>
</div>

<h2>📊 Resultados Obtidos</h2>
<p>Gráficos são gerados para demonstrar o desempenho do modelo:</p>
<ul>
    <li><b>Accurácia:</b> Taxa de acertos no conjunto de treinamento e validação.
    <li><b>Perda:</b> Erro do modelo no conjunto de treinamento e validação.
</ul>

#

<h3>✨ Autora:</h3>
<p>Desenvolvido por Juliana Soares. 😊</p>
