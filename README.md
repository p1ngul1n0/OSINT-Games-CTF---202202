# Desafios OSINT Games CTF 202202
<p style="text-align:center" align="center">
<img src="https://import.cdn.thinkific.com/568124/courses/1609487/fj6dhvJEQQKmnVw7vDto_osint-games-logo-words-149x48.png" width="20%" /><br>
<p align="center">[EM CONSTRUÇÃO]:hammer:</center></p>
</p>
Descrição e solução dos desafios do OSINT Games CTF 202202.

# Sumário
- [Zongo](#zongo)
- [The Walking Dead](#dead)
- [House of Murals](#murals)

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

 
## The Walking Dead <a name="dead"></a> ![](https://img.shields.io/badge/10%2F10-COMPLETED-blue)
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

## Country of Hoek      <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o país de origem de Hoek.

#### Solução
1. Acessando a home do site de hoeczek, é possível obter o perfil do Hack The Box, onde ele é identificado como da Polônia
> Poland
</details>  
  
  
## Projects of Hoek <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o número desenhado em uma torta que Hoek postou em um website antigo dele.

#### Solução
1. Acessando a home do site de hoeczek, é possível visualizar os projetos passados dele, como estamos em busca de uma torta, o projeto de culinária se destaca:
> nattyskitchen
2. Utilizando o WayBackMachine no ano de 2015, a foto da torta é exposta com o número:
> 27
</details>
  
## Given Name of Hoek <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o primeiro nome de Hoek através de um de seus perfis.

#### Solução
1. Acessando a home do site de hoeczek, é possível visualizar suas redes sociais, entre elas a HackerOne:
2. No perfil de Hoek na HackerOne, é exibido o primeiro nome:
> Dawid
</details>
  
## Family Name of Hoek <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o último sobrenome de Hoek.

#### Solução
1. Acessando o perfil de Hoek no Wordpress, é possível identificar que ele possuía o domínio:
> superbly.space
2. Acessando este domínio, é possível visualizar que ele não funciona mais
3. Utilizando o WayBack Machine, pode se identificar que este estava ativo entre 2016 e 2017
4. Usando um serviço de WHOIS que verifica o histórico, o nome de Hoek é exposto nos registros:
> Dawid Job

</details>
  
## Bitcoin Wallet Address of Hoek <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Identifique qual endereço bitcoin tem relação com Hoek dentre as alternativas.

#### Solução
1. Vasculhando os endereços existentes nas alternativas através do site https://www.blockchain.com, é possível visualizar que somente um existe:
>  15yT5Yv7wPaovoFWVwLvPXr2PWW8nuczht 

</details>

</details>

## House of Murals <a name="murals"></a> ![](https://img.shields.io/badge/5%2F5-COMPLETED-blue)
<details>
  <summary>Visualizar desafios</summary>

## Mural House <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
A imagem de uma casa é disponibilizada e temos que descobrir em qual cidade ela se encontra.

#### Solução
1. Buscando a imagem em serviços de busca, no caso o Bing é possível identificar diversos sites que apresentam ela
2. Acessando um destes sites, no caso designer-daily.com, o site do autor da obra, o artista Peeta é citado:
> http://www.peeta.net/works/walls/
3. No site do artista, a foto possui a seguinte legenda:
> Stadt.Wand.Kunst Mural Art Galery, Mannheim, DE, 2019
4. A cidade da obra é descoberta através da legenda da foto:
> Mannheim
</details>
  
##  Mural House Painter  <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o nome real do artista.

#### Solução
1. Acesando o site do artista e visualizando o "About", é possível visualizar que o nome real do artista é:
> Manuel Di Rita
</details>
  
</details>

