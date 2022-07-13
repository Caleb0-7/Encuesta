<!DOCTYPE html>
<link rel="stylesheet" href="facebook-logo-2019(1).png">
<link rel="stylesheet" href="estilo.css">
<link href="https://fonts.googleapis.com/css2?family=Edu+SA+Beginner:wght@500&family=Montserrat:ital,wght@1,200&family=Oswald:wght@300&family=Teko:wght@300&display=swap" rel="stylesheet"> 
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" />
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@48,400,0,0" />
<link rel="stylesheet" href="instagram(1).png">
<link rel="stylesheet" href="https://iconscout.com/icons/github">

<html>

<head>
    <title>Formulario</title>
</head>
<body >
    
    <!--Titulo-->
    <div >
        <h1 id="title">Survey for web development programmers </h1>
    </div>
    <!--Descripcion-->
    <div>
        <p id="description">Thank you for taking the time to respond</p>
    </div>
    <!--Formulario-->
    <form  id="survey-form" >
        <!--Nombre-->
        <div>
            <label id="name-label">
            Name
            <br>
            <input  id="name" size="94"  type="text" placeholder="Enter your name" required="">
            </label>
        </div>
        <!--Gmail-->
        <div>
            <label id="email-label" >
            E-mail
            <br>
            <input id="email" name="email" size="94" type="email" placeholder="Enter your email address" required>
           </label>
        </div>
        <!--Edad-->
        <div>
            
            <label id="number-label" >Age (Optional) <br><input size="94" id="number" name="Edad" type="number" min="18" max="60" placeholder="Enter your age"></label>
        </div>
        <!--Selecionar Framework-->
        <div>
           
            
            <div>
                <div id="dropdown-div">hich of the following is the framework with which you are best suited?</div>
                    
                <select   name="Favorite" id="dropdown"  >
                    
                  
                    
                    <option value="bootstrap">1.Bootstrap</option>
                    <option value=" react">2.React</option>
                    <option value="angular">3.Angular</option>
                    <option value="vuejs">4.Vuejs</option>
                    <option value="bulma">5.Bulma</option>
                </select>
            </div>    
        </div>
        <!--Seleccionar IDE-->
        
            <div><p>Select the best option for you</p></div>
            <div id="div-ide">
                <input name="option" value="Visualstudio" type="radio"  checked="">Visual Studio Code
                </label>
                <br>
                <label >
                    <input name="option" value="netbeans" type="radio"  >Netbeans
                </label>
                <br>
                <label >
                    <input name="option" value="brackets" type="radio" >Brackets
                </label>
                
            </div>
        <!--Checkbox-->
        <div><p>In which areas do you specialize (Check all that apply)</p></div>
        <div id="div-ide">
            
            <label><input value="front-end" type="checkbox">Front-end</label>
            <br>
            <label ><input value="back-end" type="checkbox">Back-end</label>
            <br>
            <label><input value="devops" type="checkbox">DevOps</label>

        </div>
        <!--Comments-->
        <div>
            <div><p>Any comments or suggestions?</p></div>
            <textarea name="comment" id="comentario"  placeholder="Enter your comment here...Please" cols="60" rows="6"></textarea>
        </div>
        <br>
        <!--Enviar-->
        <div>
            <label ><button id="submit" type="submit">Submit</button></label>
           
            
    


        </div>
        



        
    </form>
    <!--Contacto-->    
    <div id="contact">
        <a href="https://www.facebook.com/caleb.lc.9/" target="_blank"><img  id="contact-image-facebook" src="facebook-logo-2019(1).png" alt="logo-facebook"></a>
        <a href="https://www.instagram.com/caleb.lc.9/" target="_blank"><img id="contact-image-instagram" src="instagram(1).png" alt="instagram-logo"></a>
         <a href="https://github.com/CalebLC"><img id="contact-github" src="github(1).png" alt="github-logo"></a>
    </div>


    <!--Enviar-->

</body>
</html>
