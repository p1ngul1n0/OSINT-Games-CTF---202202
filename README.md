# Desafios OSINT Games CTF 202202
<p style="text-align:center" align="center">
<img src="https://import.cdn.thinkific.com/568124/courses/1609487/fj6dhvJEQQKmnVw7vDto_osint-games-logo-words-149x48.png" width="20%" /><br>
<p align="center">[EM CONSTRUÇÃO]:hammer:</center></p>
</p>
Descrição e solução dos desafios do OSINT Games CTF 202202.

# Sumário
- [Zongo](#zongo)
- [The Walking Dead](#dead)

## Zongo <a name="zongo"></a> ![](https://img.shields.io/badge/5%2F5-COMPLETED-blue)
<details>
  <summary>Visualizar desafios</summary>

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
6. Adicionalmente, vasculhando com o Google Street View ao longo das ruas que cruzam com a Zongo Lane, é possível identificar o local como sendo a latitude e longitude, na rua Asafoatse Nettey Rd:
> 5.541880857145164, -0.20993663838001453
</details>

## Blue Truck Image Latitude and Longitude  <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Definir qual é a latitude e longitude que mais se aproximam do local onde a foto foi tirada.

#### Solução
  1. Como já descoberto na solução do desafio Blue Truck Image Location, a foto foi tirada perto da rua Zongo Lane e a latitude e longitude que mais se aproximam desta localização dentre as alternativas é a:
> 5.5418955,-0.209885
</details>

## Mapillary Username   <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Identificar o usuário que realizou upload da foto do desafio no Mapillary.

#### Solução
  1. Como já descoberta a localização da foto no desafio Blue Truck Image Location, foi acessado este local no Mappilary.
  2. Ao acessar é possível identificar a foto original, sem cortes.
  3. Apartir desta foto é possível visualizar os detalhes e o usuário que a postou como:
> mawutor
</details>


##  The Full Zongo Lane <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Identificar o nome completo da Zongo Lane.

#### Solução
  1. Ao buscar Zongo Lane no Mapillary é possível obter dois resultados.
  2. Um dos resultados possui uma palavra a mais no nome, sendo:
> Kadiri
</details>

##   Longest Recording  <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Identificar o trajeto mais longo registrado por mawutor no Mappilary.

#### Solução
  1. Utilizando o filtro de trajetos do usuário mawutor, é possível visualizar claramente um trajeto cruzando de norte a sul o Congo.
  2. A cidade de ínicio deste trajeto é identificada como:
> Bawku
</details>
 
</details>

 
## The Walking Dead <a name="dead"></a> ![](https://img.shields.io/badge/2%2F5-COMPLETED-blue)
<details>
  <summary>Visualizar desafios</summary>

##  Surface Website Name  <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o domínio da surface web existente no site da darkweb.

#### Solução
1. Acessando o site e vasculhando pelas páginas, é possível visualizar o endereço na área dos termos de serviço:
> 0ut3r.space
</details>
  
##   Alternative Usernames   <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra usuários alternativos utilizados pelo usuário Hoek.

#### Solução
1. Acessando a home do site é possível visualizar diversas redes sociais que Hoek pode ser encontrado, por exemplo no Telegram, onde ele se identifica:
> hoeczek
</details>

##    Funding Goals    <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o motivo por qual Hoek pede doações.

#### Solução
1. Buscando pelo usuário alternativo do Hoek seguido da palavra Donation, é possível identificar o site ko-fi:
> "hoeczek" donation
2. No site, o perfil de hoek expõem o motivo das doações:
>  House for a zombie apocalypse
</details>  
  
##    Perfect Games    <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra qual jogo Hoek descreve como "perfeito".

#### Solução
1. Acessando o perfil da Steam de Hoek, disponibilizado na Home de seu site é possível visualizar a seção "Perfect Games, no qual um jogo é listado:
> CARRION
</details>
  
##     Site Owner's Name     <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o primeiro nome de hoeczek.

#### Solução
1. Acessando a home do site de hoeczek, ele se introduz com a frase:
> Hi, I am Hoek.
2. Expondo seu primeiro nome:
> Hoek
</details>

</details>

