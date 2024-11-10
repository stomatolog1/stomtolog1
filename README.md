<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    
   <style>
    .upfloar-log{
        display: flex;
        
   
    }
    .upfloar-read-f{
        display: flex;
       margin-left: 45em;
      padding-top: 35px;
        
    }
    .upfloar-read{
        display: flex;
        padding-top: 35px;
       
    }
    .flex-up{
        display: flex;
        justify-content: space-between;

        width: 100%;
        height: 100px;
       
    }         
    html, body {
    padding: 0;
    margin: 0;
    font-family: verdana, arial, sans-serif;
    }
 
    body {
    color: #000000;
    font-size: 1.1em;
    padding: 1em;
    display: flex;
    flex-direction: column;
    }
 
    main {
    
    display: flex;
    flex-direction: column;
    }
 
    article {
    flex: 5 2 12em;
    padding: 1em;
    
    }
    nav, aside {
    flex: 5;        
    } 
    nav {
    order: -1;
    }
     header, footer {
    flex: 0 0 2em;
        text-align: center;
    padding-left: 290px;
    padding-right: 300px;
    }
    body{
    min-height: 100vh;
    }
    main {
    flex-direction: row;
    min-height: 100%;
    flex: 1 1 auto;
    }
    .glav-gvadrat{
    
    width: 64em;
    display: flex;
    flex-wrap: wrap;   
    }
    .box1{
        display: flex;
        background: black;
        text-align:center;
        font-size: 1.1em;
        padding: 1.5em;
        width: 15em;
        height: 15em;
        margin: 10px;
    }
    .box2{
        display: flex;
        background: orange;
        text-align:center;
        font-size: 1.1em;
        padding: 1.5em;
        width: 15em;
        height: 15em;
        margin: 10px;

    }
    .box3{
        display: flex;
        background: gray;
        text-align:center;
        font-size: 1.1em;
        padding: 1.5em;
        width: 15em;
        height: 15em;
        margin: 10px;
    }
    .box4{
        display: flex;
        background: greenyellow;
        text-align:center;
        font-size: 1.1em;
        padding: 1.5em;
        width: 15em;
        height: 15em;
        margin: 10px;
    }
    .box5{
        display: flex;
        background: grey;
        text-align:center;
        font-size: 1.1em;
        padding: 1.5em;
        width: 15em;
        height: 15em;
        margin: 10px;
    }
    .box6{
        display: flex;
        background: blue;
        text-align:center;
        font-size: 1.1em;
        padding: 1.5em;
        width: 15em;
        height: 15em;
        margin: 10px;
    }
    @media screen and (max-width: 1200px) {
        .upfloar-read-f{
        display: flex;
       margin-left: 25em;
      padding-top: 35px;
        
    }
    .upfloar-read{
        display: flex;
        padding-top: 35px; 
                 
                
    }
    }
    @media screen and (max-width: 980px) {
        .upfloar-read-f{
        display: flex;
       margin-left: 39em;
      padding-top: 35px;
        
    }
    .upfloar-read{
        display: flex;
        margin-left: 5em;
        margin-right: 5em;
        padding-top: 35px; 
                 
                
    }
        header, footer {
        flex: 0 0 2em;
        text-align: center;
        margin-left: 4em;
        width: 20em;
        height: 15em;
    }
    .glav-gvadrat{
        margin-left: 10em;
   width: 60em;
   display: flex;
   flex-wrap: wrap;
    }
    }
    @media screen and (max-width: 780px){
    .box1{
        display: flex;
        background: black;
        text-align:center;
        font-size: 1.1em;
        padding: 1.5em;
        width: 20em;
        height: 20em;
        margin: 10px;
    }
    .box2{
        display: flex;
        background: orange;
        text-align:center;
        font-size: 1.1em;
        padding: 1.5em;
        width: 20em;
        height: 20em;
        margin: 10px;

    }
    .box3{
        display: flex;
        background: gray;
        text-align:center;
        font-size: 1.1em;
        padding: 1.5em;
        width: 20em;
        height: 20em;
        margin: 10px;
    }
    .box4{
        display: flex;
        background: greenyellow;
        text-align:center;
        font-size: 1.1em;
        padding: 1.5em;
        width: 20em;
        height: 20em;
        margin: 10px;
    }
    .box5{
        display: flex;
        background: grey;
        text-align:center;
        font-size: 1.1em;
        padding: 1.5em;
        width: 20em;
        height: 20em;
        margin: 10px;
    }
    .box6{
        display: flex;
        background: blue;
        text-align:center;
        font-size: 1.1em;
        padding: 1.5em;
        width: 20em;
        height: 20em;
        margin: 10px;
    }
    .glav-gvadrat{
        margin-left: 7em;
   width: 60em;
   display: flex;
   flex-wrap: wrap;
    }
    header, footer {
        flex: 0 0 2em;
        text-align: center;
        margin-left: 5em;
        width: 25em;
        height: 15em;
    }
    @media screen and (max-width: 580px){
        header, footer {
        flex: 0 0 2em;
        text-align: center;
        margin-left: 3em;
        width: 25em;
        height: 15em;
    }
        .glav-gvadrat{
        margin-left: 15em;
   width: 35em;
   display: flex;
   flex-wrap: wrap;
    }
    .box1{
        display: flex;
        background: black;
        text-align:center;
        font-size: 1.1em;
        padding: 1.5em;
        width: 25em;
        height: 25em;
        margin: 10px;
    }
    .box2{
        display: flex;
        background: orange;
        text-align:center;
        font-size: 1.1em;
        padding: 1.5em;
        width: 25em;
        height: 25em;
        margin: 10px;

    }
    .box3{
        display: flex;
        background: gray;
        text-align:center;
        font-size: 1.1em;
        padding: 1.5em;
        width: 25em;
        height: 25em;
        margin: 10px;
    }
    .box4{
        display: flex;
        background: greenyellow;
        text-align:center;
        font-size: 1.1em;
        padding: 1.5em;
        width: 25em;
        height: 25em;
        margin: 10px;
    }
    .box5{
        display: flex;
        background: grey;
        text-align:center;
        font-size: 1.1em;
        padding: 1.5em;
        width: 25em;
        height: 25em;
        margin: 10px;
    }
    .box6{
        display: flex;
        background: blue;
        text-align:center;
        font-size: 1.1em;
        padding: 1.5em;
        width: 25em;
        height: 25em;
        margin: 10px;
    }
    }
    }
</style>
</head>
<body>
    <div class="flex-up">
      <div class="upfloar-log"><h1>Nicepage</h1></div>
      <div class="upfloar-read-f">home</div>
      <div class="upfloar-read">About Company</div>
    </div>
</body>
<body>
    <header>
        <h1>We'll help manage your business</h1>
        <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa</p>
    </header>
    <main>
        <article>
            <div class="glav-gvadrat">
                <div class="box1">Consultations</div>
                <div class="box2">Strategy</div>
                <div class="box3">Investment</div>
                <div class="box4">Marketing</div>
                <div class="box5">Startups</div>
                <div class="box6">Anti-Crisis</div>
            </div>
        </article>
        <nav>
        </nav>
        <aside>
        </aside>
    </main>
    
</body>

</html>
