<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    /* crée une classe text_style et dans le css tu l'appelle et mets ce font-family :[Hanken Grotesk](https://fonts.google.com/specimen/Hanken+Grotesk) puis tu definis le font size général de 18px et tu laisse les titre tel quels*/
    .Summary{
        color: hsl(228deg 24.14% 28.43%);
    }
    .Summary-item{
        border-radius: 4px;
        width: 200px /* je peux essayer avec 100%*/ ; 
        height: 20px;
        margin: 10px;
    }
    .Summary-item1{
        background-color: hsl(6deg 100% 98.04%);    
    }
    .Summary-item2{
        background-color: hsl(41.54deg 100% 97.45%);    
    }
    .Summary-item3{
        background-color: hsl(173.33deg 52.94% 96.67%);    
    }
    .Summary-item4{
        background-color: hsl(240deg 71.43% 97.25%);    
    }

    .button{
        width: 100px;
        border-radius: 10px ;
        border: none;
        margin-top: 15px;
        background-color: hsl(243.49deg 84% 55.88%);
    }
</style>
<body>
    <div>
        <h2 class="Summary">
            Summary
        </h2>
    </div>
    <div class="Summary-item1 Summary-item"> 
        Reaction 80 / 100
    </div>
    <div class="Summary-item2 Summary-item">
        Memory 92 / 100
    </div>
    <div class="Summary-item3 Summary-item">
        Verbal 61 / 100
    </div>
    <div class="Summary-item4 Summary-item">
        Visual 72 / 100
    </div>
    <button class="button">Continue</button>
</body>
</html>