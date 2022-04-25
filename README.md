# Desafios OSINT Games CTF 202202
<p style="text-align:center" align="center">
<img src="https://import.cdn.thinkific.com/568124/courses/1609487/fj6dhvJEQQKmnVw7vDto_osint-games-logo-words-149x48.png" width="20%" /><br>
<p align="center">[EM CONSTRUÇÃO]:hammer:</center></p>
</p>
Descrição e solução dos desafios do OSINT Games CTF 202202.

# Sumário
- [Blue Truck Image Location](#Blue-Truck-Image-Location)


## Blue Truck Image Location <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
A imagem de uma rua é disponibilizada e temos que descobrir a cidade na qual ela se encontra.

#### Solução
1. Visualizando a imagem é possível identificar duas palavras:
> SOCCABET
> Zongo La
2. Fazendo uma busca por estes dois termos juntos, o Google nos trará o nome de uma via próxima ao local da foto::
> Zongo Lane
3. Buscando por Zongo Lane no Google Maps, é possível identificar que esta via é localizada em uma cidade na Gana:
> Accra
4. Buscando novamente no Google Maps pelo termo abaixo, é possível confirmar que uma unidade da SOCCABET se encontra próxima a via Zongo Lane, em Accra no Congo:
> Zongo Lane SOCCABET
5. A FLAG é enviada como:
> Accra
</details>

## Blue Truck Image Latitude and Longitude  <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Definir qual é a latitude e longitude que mais se aproximam do local onde a foto foi tirada.

#### Solução
  1. Como já descoberto na solução do desafio Blue Truck Image Location, a foto foi tirada na junção da rua Prof. Atta Mills High St com a Ga Mashie RD e a latitude e longitude que mais se aproximam desta localização dentre as alternativas é a:
> 5.5418955,-0.209885
</details>

