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
- [All Decked Out](#decked)
- [Guitar Riffs](#guitar)

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

## House of Murals <a name="murals"></a> ![](https://img.shields.io/badge/2%2F2-COMPLETED-blue)
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

## All Decked Out <a name="murals"></a> ![](https://img.shields.io/badge/12%2F12-COMPLETED-blue)
<details>
  <summary>Visualizar desafios</summary>

## Deck The Halls <a name="decked">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o site do Influencer adoriandeck que redireciona para seu linktr.ee.

#### Solução
1. Buscando pelo nome do influencer no Google, é possível visualizar seu Instagram
2. Na Bio de seu Instagram o site que redireciona para seu linktr.ee:
> adoriandeck.com
</details>
  
## Hot Mail  <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o e-mail de Adorian.

#### Solução
1. Acessando o site de Adorian (adoriandeck.com) no WayBack Machine em 2012, é possível visualizar o seu e-mail
> adoriandeck@gmail.com
</details>
  
##  Shop Local <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o site de e-commerce da Shopify que Adorian possui, onde o nome tem o nome de seu cachorro.

#### Solução
1. Acessando o linktr.ee é possível visualizar o link para o e-commerce que possui o nome:
> tinycrumble.com
</details>
  
##   Vid Bros <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o canal de Youtube que Adorian possui junto com seu irmão.

#### Solução
1. Buscando pelos vídeos do canal de Adorian, é possível identificar o canal de seu irmão
2. Acessando o canal de seu irmão (Adrian), o canal que possui junto ao seu irmão está registrado como um canal parceiro:
> The Deck Brothers
</details>
  
## IG me <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o Instagram do irmão de Adorian.

#### Solução
1. Acessando o canal do Youtube de Adrian, seu Instagram está como rede social:
> adrianedwarddeck
</details>
  
##  Early Adopter <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o Instagram do irmão de Adorian.

#### Solução
1. Comparando a data de inscrição de ambos canais de Adorian e Adrian, fica evidente que Adorian se cadastrou antes no Youtube:
> Adorian
</details>
  
##   #Banned <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o Twitter que os irmãos utilizavam e que agora é banido.

#### Solução
1. No Youtube dividido pelos dois irmãos, o Twitter é disponibilizado:
> thedeckbrothers
</details>

## Name In Lights  <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o nome da jornalista que entrevistou Adorian em 26 de julho de 2014.

#### Solução
1. Realizando uma busca no Google é possível obter a entrevista de Adorian
2. Acessando a entrevista o nome da entrevistadora é identificada:
> TANYSHA BOLGER
</details>
  
##  Dropped Calls  <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra a operadora que Adorian utilizava na época da entrevista.

#### Solução
1. A entrevista contém uma captura de tela do celular de Adorian, que expõe o nome da operadora utilizada:
> Verizon
</details>
  
##  Entrepreneurial Spirit <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é a LLC da empresa de Adorian.

#### Solução
1. Buscando pelo nome da empresa de Adorian (Derick Media) seguida pela sigla LLC no Google, o site DNB é encontrado
2. Acessando este site é possível identificar a LLC da empresa:
> Decked Out Media
</details>
  
## Coast To Coast  <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual outro estado dos EUA a Derick Out Media esta registrada além da California.

#### Solução
1. Buscando pelo nome da empresa de Adorian (Derick Out Media) o site OpenCorporates é encontrado
2. Acessando este site é possível identificar que a empresa esta localizada na Florida:
> Florida
</details>
  
##  Sue Me <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual empresa que Adorian processou em 2011.

#### Solução
1. Buscando pelo termo abaixo no Google é possível encontrar uma notícia que expõe o nome que Adorian Decker processou em 2011:
> adorian deck lawsuit
2. O nome da empresa é:
> Spartz
</details>
  
</details>


## Guitar Riffs <a name="guitar"></a> ![](https://img.shields.io/badge/10%2F10-COMPLETED-blue)
<details>
  <summary>Visualizar desafios</summary>

## John Legend <a name="decked">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o sobrenome do músico chamado John mencionado no site da imagem.

#### Solução
1. Buscando por termos que aparecem na imagem é possível achar o site:
> "ABOUT JOHN" "Mel Holder"
2. No site é possível visualizar que o sobrenome é:
> Smith
</details>
  
 ##  Look Up <a name="decked">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o site que aparece na imagem.

#### Solução
1. Como o site já foi descoberto no desafio anterior (John Legend) é apenas uma questão de responder:
> axxanpro23.com
</details>
  
## Start Date  <a name="decked">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é a data de criação do canal do Youtube de John

#### Solução
1. Clicando no botão "WATCH MORE VIDEOS" é possível acessar o canal do Youtube de John e a data de criação é:
> March 6, 2006
</details>
  
## The Gig  <a name="decked">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o e-mail para contratar John

#### Solução
1. No Footer do site existe um botão de e-mail:
> Axxan23@yahoo.com
</details>
  
## It's Me Again   <a name="decked">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o outro site que John possui que redireciona para o site atual

#### Solução
1. No canal de Youtube de John é possível obter o link para outro site:
> itsjohnsmith.com
</details>
  
## Take Me To Church  <a name="decked">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Um dos sites de John foi registrado no nome de uma igreja, qual é ela

#### Solução
1. Fazendo uma consulta no WhoIs pelo domínio abaixo:
> itsjohnsmith.com
2. É possível identificar a igreja:
> Faith Baptist Church
</details>
  
## Throwback <a name="decked">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual era o usuário de John no MySpace

#### Solução
1. Acessando o Facebook de John é possível visualizar um link para seu MySpace com o usuário:
> axxan23
</details>
  
##  5 Stars <a name="decked">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o produto que John avaliou no Sourceforge em 2014-12-03

#### Solução
1. Realizando uma busca no Google com o seguinte termo:
> inurl:sourceforge.net/projects  intext:Posted 2014-12-03
2. É possível obter o produto que John avaliou, no caso:
> Fx FloorBoard
</details>
  
## Pay The Man <a name="decked">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual usuário John utiliza para doações financeiras
  
#### Solução
1. Visualizando os vídeos existentes no canal de John, é possível visualizar na descrição o usuário utilizado para doações:
> $Axxanpro23
</details>
  
## Look Back <a name="decked">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual site John registrou utilizando seu e-mail pessoal
  
#### Solução
1. Utilizando um serviço de consulta reversa (www.reversewhois.io), é possível identificar o site:
> fbccny.org
</details>

</details>
