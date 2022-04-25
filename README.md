# Desafios OSINT Games CTF 202202
<p style="text-align:center" align="center">
<img src="https://user-images.githubusercontent.com/17954762/47567241-4b4f2080-d92e-11e8-830c-b5db21beab69.png" width="10%" /><br>
<p align="center">[EM CONSTRUÇÃO]:hammer:</center></p>
</p>
Descrição e solução de LABs da Burp Academy.

# Sumário
- [Blue Truck Image Location](#Blue-Truck-Image-Location)


## Blue Truck Image Location <a name="Blue-Truck-Image-Location"></a>
##### [![](https://img.shields.io/badge/Voltar-Sum%C3%A1rio-orange)](#sumário)

<details>
  
<summary>:bulb:</summary>

1. Autentique e acesse a área do usuário.
2. É possível identificar o uso do seguinte endpoint:
> GET /accountDetails
3. Este endpoint retorna a API Key do usuário autenticado:
```
 {
   "username": "wiener",
   "email": "",
   "apikey": "BDKD9r0wSagpq7fIN6DlyMkmVd8BPVWs",
   "sessions": [
     "VB2znrX8xyrGsfeFTCb7Dv1VBkL5DTuQ"
   ]
 }
```  
3. Programe um código JavaScript para realizar uma requisição GET para o endpoint identificado e obter a API Key.
4. Este código também deve enviar a API Key para o servidor de exploit.
5. O código deve ser armazenado no servidor de exploit e entregue para a vítima.
6. Após o último passo, a API Key deve aparecer no log do servidor de exploit:
>  GET /?apikey=V8YQnKjWB8oGz0YD6tjO4r8V8itPe6Jc
</details>

