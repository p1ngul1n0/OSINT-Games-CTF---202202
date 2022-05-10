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
- [In the Business](#business)
- [The Life](#life)
- [Oskar Blues](#oskar)
- [The Rabbit Hole](#rabbit)
- [The Comission](#comission)
- [The Narrow Road](#narrow)
- [Maja](#maja)
- [The Sphynx](#sphynx)

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

## In The Business <a name="business"></a> ![](https://img.shields.io/badge/12%2F12-COMPLETED-blue)
<details>
  <summary>Visualizar desafios</summary>

##  Big MAC <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o SSID relacionado ao BSSID disponibilizado.

#### Solução
1. Utilizando Wigle e realizando uma consulta pelo BSSID, o SSID é identificado:
> Sly and Co
</details>
  
##  Suite Digs <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual o número da suíte que a empresa ocupa.

#### Solução
1. Acessando o site da empresa (slyandcogroup.com) é possível identificar o número da suíte como:
> 200
</details>
  
## MX Me <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o prefixo do endereço de e-mail que a empresa utiliza para informações.

#### Solução
1. Acessando o site da empresa (slyandcogroup.com) é possível identificar o prefixo como:
> slyandco.com
</details>
  
## Google Knows All <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual das alternativas não compartilha do mesmo Google Tracking ID.

#### Solução
1. Realizando uma busca pelo site no host.io, é possível verificar mais três domínios que utilizam o mesmo ID, exceto:
> slyandcompany.com
</details>
  
## Redirect Your Attention  <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual site redireciona para slyandco.com e possui o prefixo "ca".

#### Solução
1. Realizando uma busca pelo site no host.io, é possível verificar que o seguinte domínio redireciona para o site:
> slyandco.ca
</details>
  
## Former Employees   <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o funcionário que trabalhou como "Production Designer" na filial Ookpik entre 2015 e 2019

#### Solução
1. Realizando uma busca pelo termo abaixo no LinkedIn:
> Production Director Ookpik
2. Descobrimos que o nome da funcionária é:
> Chrissy Alexakis
</details>

##  Pink Lil <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual boutique da Nova Zelândia vende produtos da Sly & Co e fica entre uma floricultura e uma padaria

#### Solução
1. Realizando uma busca pelo termo abaixo no Google:
> intext:Sly and Co florist bakery
2. Descobrimos que o site da boutique é:
> furtherdoings.co.nz
</details>
  

## Land Ho  <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é a cidade de destino de uma entrega da Sly & Co de 6 de julho de 2020

#### Solução
1. Realizando uma busca pelo termo abaixo no Google:
> "Sly Co" "shipment" after:2020-07-05 before:2014-07-07
2. Descobrimos um site que lista as ordens, sendo possível identificar o endereço como:
> Seattle, Washington
</details>
  
##  HMS Titanic <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o nome do navio que fez a entrega do desafio anterior

#### Solução
1. Realizando uma busca pelo termo abaixo no Google:
> "Sly Co" "shipment" after:2020-07-05 before:2014-07-07
2. Descobrimos um site que lista as ordens, sendo possível identificar o navio como:
> APL QINGDAO
</details>
  
## Roger That <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o callsign do navio que fez a entrega do desafio anterior

#### Solução
1. Realizando uma busca pelo nome do navio no site itu.int, é possível identificar o callsign como:
> 9HA5178
</details>
  
## Roger That <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é registro de marca que Sly and Co realizou em 20 de junho de 2017

#### Solução
1. Realizando uma busca pela empresa Sly and Co no site trademarks.justia.com é possível identificar o número do registro como:
> 1843714
</details>
  
##  Hello World! <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o nome de um famoso jogo de celular que está em um template identificado no sitemap de um dos sites da Sly & Co

#### Solução
1. Acessando a URL abaixo do sitemap de slyandcogroup.com:
> https://slyandcogroup.com/wp-sitemap-posts-post-1.xml
2. É possível identificar o nome do jogo como:
> Farmville
</details>
  
</details>

## The Life <a name="life"></a> ![](https://img.shields.io/badge/3%2F3-COMPLETED-blue)
<details>
  <summary>Visualizar desafios</summary>

##  4 Letter Words <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Identifique a conta do Instagram que postou uma foto marcando o usuário @udontshoot e com a legenda "Quick pizza 🍕 before take off 🛩📸".

#### Solução
1. Realizando uma simples busca no Google com o termo abaixo:
> @udontshoot Quick pizza 🍕 before take off 🛩📸
2. É possível identificar a conta como sendo:
> rkoi
  
</details>
  

##   Carpool Lane <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Identifique a rua em que o vídeo disponibilizado foi filmado.

#### Solução
1. Visualizando o vídeo, é possível identificar o estabelecimento "Valley Country Market", buscando no Google Maps o endereço é:
> Ventura
  
</details>
  
## Alternate Communications <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o código HEX do avião presente na foto postado por @rkoi em 22 de julho de 2021.

#### Solução
1. Visualizando a foto é possível identificar o código N do avião como:
> N39AC
2. Consultando este código no site registry.faa.gov, é possível identificar o código HEX como:
> A48073
  
</details>
  
</details>


## Oskar Blues <a name="oskar"></a> ![](https://img.shields.io/badge/7%2F7-COMPLETED-blue)
<details>
  <summary>Visualizar desafios</summary>

## Insta Famous <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o usuário do Instagram de Oskar J.C.

#### Solução
1. Realizando uma simples busca no Google pelo nome de Oskar seguido por Instagram, o usuário é descoberto:
> blckmny
</details>

## AMOSC <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o usuário do Snapshat de Oskar J.C.

#### Solução
1. Acessando o canal de Youtube de Oskar é possível obter seu snapchat:
> blckmnyofficial
</details>
  
## Book Me <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o e-mail de negócios de Oskar.

#### Solução
1. Acessando o canal de Youtube de Oskar é possível obter seu e-mail de negócios:
> blckmnyvlogs@gmail.com
</details>
  
## Too Fast <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Descubra o carro que Oskar dirige.

#### Solução
1. Acessando o seu Instagram fica evidente que o carro que Oskar dirige é:
> Audi R8
</details>
  
## Sweet Ride <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual a marca de carro que está na foto de Oskar no Google.

#### Solução
1. Utilizando o e-mail de negócios de Oskar descoberto anteriormente, é possível identificar que a marca do carro é:
> BMW
</details>
  
## Formal Papers <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual a data de primeiro registro da BMW azul que Oskar possuía.

#### Solução
1. Visualizando fotos mais antigas do Instagram de Oskar, é possível visualizar a placa original da BMW:
> BT38517
2. Utilizando um serviço da Noruega (vegvesen.no) é possível identificar que a data de registro é:
> January 1, 2012
</details>
  
##  Name Game  <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual são os dois sobrenomes de Oskar.

#### Solução
1. A URL do Youtube de Oskar possui o nome:
> Oskar Czop
2. Fazendo uma busca por este nome no Google, resulta em um vídeo de uma notícia, na qual a descrição do vídeo expõe o sobrenome dele como:
> Jaroslaw Czop
</details>
  
</details>

## The Rabbit Hole <a name="rabbit"></a> ![](https://img.shields.io/badge/12%2F12-COMPLETED-blue)
<details>
  <summary>Visualizar desafios</summary>

##  Bye Bye Bye! <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
A imagem de um carro é disponibilizada e temos que descobrir a rua na qual ela se encontra.

#### Solução
1. Visualizando a imagem é possível identificar o nome de um estabelecimento:
> Hans Crescent
2. Fazendo uma busca pelo nome do edíficio no Google Maps, identificamos que este se encontra na rua Basil em Londres:
> Basil
</details>
  

## The ABCs  <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual eram as duas letras em um adesivo que estavam coladas na caixa verde abaixo do nome do edíficio.

#### Solução
1. Visualizando registros anteriores do Google Street (setembro de 2017) é possível identificar as letras:
> po
</details>
  
## The Scofflaw  <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Em que mês e ano um sedan da Mercedes foi fotografado na mesma vaga.

#### Solução
1. Visualizando registros anteriores do Google Street (maio de 2016) é possível um sedan branco estacionado no mesmo local
</details>
  
##  Looney Tunes <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Encontre o canal de Youtube relacionado ao adesivo colado.

#### Solução
1. Buscando pela imagem no Yandex com o denominador site:youtube.com é possível encontrar o canal:
> psychomartv
</details>

##   Web "Presents" <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o website associado ao psychomartv.

#### Solução
1. Acessando o Tiktok de psychomartv é possível identificar o site como:
> psychomar.com
</details>
  
## What's in a Name  <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o nome e sobre nome de psychomartv.

#### Solução
1. Acessando o Facebook de psychomartv é possível identificar o seu nome e sobrenome pelo e-mail de contato disponibilizado:
> Omar Mohidin
</details>
  
##  Registration Crumbs <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o e-mail que Omar utilizou para registrar o domínio psychomar.com em 2016.

#### Solução
1. Utilizando um serviço de busca de histórico de WhoIS (https://tools.whoisxmlapi.com/whois-history-search) é possível identificar o e-mail:
> o.mohidin@outlook.com
</details>
  
##   Book It <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o e-mail que Omar utiliza para negócios.

#### Solução
1. Visualizando o canal do Youtube de Omar é possível identificar o e-mail:
> Info@Psychomar.com
</details>
  
## It's Me, I Promise <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o outro sobrenome de Omar que aparece no seu perfil do Periscope.

#### Solução
1. Apesar do Periscope ter sido descontinuado em 2021, ainda é possível visualizar os perfis dos usuários, como já conhecemos o @ de Omar, formulamos a URL:
> https://www.pscp.tv/PsychomarTV
2. Acessando a URL temos o perfil de Omar que exibe o sobrenome:
> Ozi
</details>
  
##  Let's Dance <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é a data que Omar postou seu primeiro vídeo no Youtube.

#### Solução
1. Acessando o canal do Youtube do Omar podemos ver que a data de postagem do seu primeiro vídeo é:
> January 25, 2015
</details>
  
## Razor Sharp <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é a rua que o estabelecimento da foto se encontra.

#### Solução
1. Buscando as palavras encontradas na foto no Google Maps:
> Psycho Cu
2. Encontramos a barbearia Psycho Cutz em Londres que fica na rua:
> High
</details>
  
##  Google It <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual são os últimos 4 digitos do ID da conta Google de Omar.

#### Solução
1. Buscando um dos e-mails descobertos anteriormente (o.mohidin@outlook.com) na ferramenta Ghunt, o ID é retornado:
> 2704
</details>
  
</details>

## The Commission <a name="comission"></a> ![](https://img.shields.io/badge/11%2F11-COMPLETED-blue)
<details>
  <summary>Visualizar desafios</summary>

## jointcommission Email  <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o servidor de e-mail de jointcommission.org

#### Solução
1. Realizando uma busca pelo site mxtoolbox.com, é possível identificar que o servidor de e-mail é:
> jointcommission-org.mail.protection.outlook.com
</details>
  
## Cohosted Domain <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o site dentre as alternativas que divide o mesmo IP que jointcommission.org.

#### Solução
1. Realizando uma busca no site host.io por jointcommission.org é possível identificar que o site é:
> jcaho.org
</details>
  
##  Historic WHOIS Email <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o e-mail que esta no histórico de registros do WHOIS.

#### Solução
1. Realizando uma busca pelo domínio no serviço (tools.whoisxmlapi.com/whois-history-search) é possível identificar que o e-mail é:
> kstehlik@jointcommission.org
</details>
  
## Email Pivot to Websites <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual rede social das alternativas o e-mail kstehlik@jointcommission.org está conectado.

#### Solução
1. Realizando uma busca pelo e-mail no serviço (epieos.com) é possível identificar que o e-mail está conectado ao:
> Github
</details>
  
## jointcommission Email2 <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é a empresa que administra os servidores de e-mail de jointcommission.org.

#### Solução
1. Realizando uma busca no site host.io por jointcommission.org é possível identificar que a empresa é a abaixo, visto que possui "outlook":
> Microsoft
</details>
  
## s4bweb IP <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o IP que o domínio s4bweb-dr.jointcommission.org resolve.

#### Solução
1. Realizando uma busca no site who.is por s4bweb-dr.jointcommission.org é possível identificar que o IP é:
> 198.143.155.155
</details>
  
##  Username to Websites <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Em qual dos sites das alternativas possui uma conta com o usuário de kstehlik.

#### Solução
1. Realizando uma busca no site whatsmyname.app por kstehlik é possível que a rede social é:
> GitHub.com
</details>
  
## GitHub Profile  <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Em que dia o usuário kstehlik publicou no Github que estava na Cisco.

#### Solução
1. Acessando o perfil do usuário é possível visualizar que esta publicação foi feita em:
> April 15, 2015
</details>
  
## Reddit Account Creation <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Em que dia o usuário kstehlik criou sua conta no Reddit.

#### Solução
1. Acessando o perfil do usuário é possível visualizar que ele se cadastrou em:
> March 27, 2019
</details>
  
## WHOIS Email Pivoting <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o outro domínio que o e-mail kstehlik@jointcommission.org registrou dentre as alternativas.

#### Solução
1. Realizando uma busca pelo domínio no serviço (tools.whoisxmlapi.com/whois-history-search) é possível identificar que o domínio é:
> jcahosucks.org
</details>
  
## Username to Person Name  <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
O usuário kstehlik tem uma conta na Venmo que expõe seu nome e sobrenome, quais são eles

#### Solução
1. Como estamos localizados no Brasil, é necessário o uso de uma VPN para que possamos acessar a Venmo, pois ela é restrita aos EUA
2. Com uma VPN com localização dos EUA, o site de mapeamento de contas "WhatsmynameWeb" é utilizado buscando pelo usuário 'kstehlik', que resulta em positivo para uma conta Venmo
3. Acessando o link https://account.venmo.com/u/kstehlik é possível idetentificar o nome do usuário como:
> Kaitlyn Stehlik
</details>
</details>

## The Narrow Road <a name="narrow"></a> ![](https://img.shields.io/badge/4%2F4-COMPLETED-blue)
<details>
  <summary>Visualizar desafios</summary>

## Camera Model Name <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o modelo da câmera que tirou a foto em anexo.

#### Solução
1. Utilizando o ExifTool é possível ver que o modelo da câmera é:
> COOLPIX P6000
</details>
  
## Date Image Taken <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é a data de criação da foto.

#### Solução
1. Utilizando o ExifTool é possível ver que a data de criação da foto é:
> 10-22-2008
</details>
  
## GPS Position of Image  <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é a latitude e longitude da foto.

#### Solução
1. Utilizando o site exif.regex.info/exif.cgi é possível visualizar que a latitude e longitude da foto é:
> 43.4672,11.8792
</details>
  
## Lat/Lon to Town Name  <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é a cidade próxima da latitude e longitude da foto.

#### Solução
1. Utilizando o Google Maps é possível visualizar que a cidade próxima da latitude e longitude da foto é:
> Arezzo
</details>

</details>

## Maja <a name="maja"></a> ![](https://img.shields.io/badge/9%2F9-COMPLETED-blue)
<details>
  <summary>Visualizar desafios</summary>

## Call me <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o telefone presente em um dos sites de Maja

#### Solução
1. Acessando o perfil de Maja, é possível visualizar na BIO o perfil @weyhe.official que possui o site weyhe.website
2. Que possui o número de contato:
> 49017630650451
</details>
  
## The Old Me <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual website que redireciona para majaweyhe.com

#### Solução
1. Consultando o site majaweyhe.com no serviço host.io, é possível visualizar que o website que redireciona é:
2. majawyh.com
</details>

## Make It Official <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Em que ano a empresa Weyhe GmbH foi registrada

#### Solução
1. Consultando a empresa no dnb.com, é possível visualizar que ela foi registrada em:
2. 2019
</details>
  
## Reader's Choice <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Em qual revista Weyhe ganhou o prêmio Best German Style Blog em 2015

#### Solução
1. Realizando uma busca no Google pelo termo:
> "Best German Style Blog" 2015 Weyhe
2. É possível identificar que a revista foi:
> Jolie
</details>
  
## That's a Throwback <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual e-mail Maja utilizava anteriormente

#### Solução
1. Verificando o antigo site majawyh.com no WayBack Machine é possível verificar que em 2013 o e-mail utilizado era:
> majawyh@gmx.de
</details>

## World Traveler <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Em qual cidade Maja morava em 2013

#### Solução
1. Verificando o antigo site majawyh.com no WayBack Machine é possível verificar que em 2013 Maja morava em:
> Vienna
</details>
  
## I Thought You Said Lunch <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual lançamento de livro Maja foi fotografa em 25 de novembro de 2014

#### Solução
1. Buscando pelo termo no Getty Images:
> maja wyh book
2. É possível identificar o livro como:
> Tory Burch
</details>

## Check Out The Hook <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual era o DJ no lançamento de livro que Maja foi fotografa em 25 de novembro de 2014

#### Solução
1. Buscando pelo termo no Getty Images:
> 'Tory Burch: In Color' Book Launch In Munich DJ
2. É possível identificar o DJ como:
> Nikias Hofmann
</details>
  
## Uncle Sam in Dusseldorf <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o identificador de TAX de Weyhe

#### Solução
1. Acessando o site de Weyhe é possível identificar o TAX como:
> DE325872931
</details>

</details>

## The Sphinx <a name="sphynx"></a> ![](https://img.shields.io/badge/1%2F1-COMPLETED-blue)
<details>
  <summary>Visualizar desafios</summary>

## Lifted <a name="Blue-Truck-Image-Location">:heavy_check_mark:</a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-blue)](#sumário)

<details>
  
<summary>:bulb:</summary>
  
#### Descrição
Qual é o site original da imagem

#### Solução
1. Por mais qu e a imagem esteja em baixa qualidade é possível identificar algumas palavras como:
> Award of Excellence
> The International Cat Association
> MEADOW
> SPHYNX
> 2018
> TCA
2. Realizando uma busca no DuckDuckGo com o os termos abaixo:
> TCA "award of excellence" "sphynx" "meadow" "2018" inurl:.ru
3. É possível identificar o site como:
> meadowsphynx.co.uk
</details>
</details>
