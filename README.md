# Spotify EDA e Previsão de Likes

A análise foi realizada utilizando a base retirada do spotify disponibilizada no www.kaggle.com.

A motivação da análise é entender os fatores que influenciam uma pessoa a gostar ou não de uma música que foi recomendada para elas. Sendo importante para definir quais características em comum podem gerar uma maior aceitação do público para música. Tentando prever a partir dos fatores, quais músicas receberiam um like ou deslike.

Dataset: https://www.kaggle.com/datasets/bricevergnou/spotify-recommendation?select=data.csv

Estatística Descritiva da base

* danceability: "Danceabilidade" da música.
* energy: Percepção de intensidade da música.
* key: Classe de notas.
* loudness: Sonoridade das músicas em dB.
* mode: Modalidade da música.
* speechiness: Detecta a presença de palavras cantadas durante a música.
* acousticness: Medida de acústica da música.
* instrumentalness: Partes da música que não possui vocais.
* liveness: Detecta a presença de público durante a gravação.
* valence: Descreve a positividade da música.
* tempo: Tempo estimado de batidas por minuto.
* duration_ms: Duração da música em milisegundos.
* time_signature: Verificar quantas batidas há em cada compasso.
* liked: Variável para ser predita, se a música recebeu um like (1) ou deslike (0)

Utilizando o algoritmo de machine learnin decision tree para prever os likes, chegamos a uma acurácia de 88% aproximadamente, plotagem da árvore abaixo:

![image](https://github.com/LucasMarchesoni/Spotify-EDA-e-Previs-o-de-Likes/assets/133407474/0cb088ae-7edc-4f38-9f9d-9f13c5006435)
