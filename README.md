# Site danki login
### criei essa tela com base na original da danki

### Pré visu:
![Pré visu](previsu.png)

## HTML:
```
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadastrar formulario com suas credencias Danki</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <section>
    <div class="logo">
        <img src="img/logo.png" alt="Logo">
    </div>
    <form action="eita">
        <h1>Acesse sua conta</h1>
        <h3>E-mail</h3>
        <input type="email" name="fmail" placeholder="Digite seu e-mail..." id="fmail">
        <h3>Senha</h3>
        <input type="password" name="fsenha" id="fsenha" placeholder="Digite sua senha...">
        <div>
        <button type="submit">Enviar</button>
      </div>
      <div>
      <h5>Esqueci minha senha</h5>
        <p>Não possui conta ainda?</p>
        <p>Criar conta gratís</p>
    </div>
    </form>
</section>
</body>
</html>
```

## CSS:
```
    *{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    resize: none;
}
html,body{
    height: 100%;
    font-weight: normal;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
}
section{
    background-image: url('../img/banner_banner.jpg');
    width: 100%;
    height: 100%;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    position: absolute;
} 
section > .logo{
    margin: 60px;
}
section > form h1{
    color: #FFFFFF;
    font-size: 33px;
    margin: 60px;
}
section > form h3{
    color: #FFFFFF;
    margin: 15px 60px;
}
section > form input{
    color: #8A607E;
    background-color: #231121;
    width: 365px;
    height: 46px;
    transition: 0.3s;
    margin: 0 60px;
    border: 1px solid #5f5f5f6e;
    padding: 10px;
    border-radius: 10px;
    outline: none;
}
section > form > div button{
    margin: 40px 60px;
    width: 107px;
    height: 40px;
    font-size: 17px;
    background-color: #311735;
    border: none;
    border-radius: 10px;
    color: #FFFFFF;
    cursor: pointer;
    transition: 0.3s;
}
section > form > div:nth-of-type(2){
    color: #FFFFFF;
    margin: 0 60px;
    cursor: pointer;
}
section > form h5,p{
    margin: 2px;
    transition: 0.3s;
}
section > form h5,p:hover{
    color: #CCCCCC;
}
section > form > input:focus{
    color: #FFFFFF;
}
section > form > div > button:hover{
    background-color: #231121fa;
}
```

##### **Não responsivo**