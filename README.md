# CONTACT-FORM
Done a basic project using HTML and CSS


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contact form</title>
</head>
<style>
    .wait{
        text-align: center;
        width: 50%;
        height: 50%;
        padding-left: 25%;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .background{
        background-image: url(anime_boy-removebg.png);
        background-repeat: no-repeat;
        background-color: rgb(0, 0, 0);
        width: 100%;
        height: 100%;
        padding-left: 10%;
        padding-right: 10%;
        padding-top: 10%;
        padding-bottom: 10%;
        text-align: center;

    }
    .main{
        width: 40vw;
        text-align: center;
        background-color: rgba(255, 255, 255, 0.33);
        border: 50px;
        color: rgb(0, 0, 0);
        padding-left: 20px;
        padding-right: 20px;
        padding-top: 20px;

        font-family:Georgia, 'Times New Roman', Times, serif;
        font-weight: 600;
        font-size: xx-large;
    }
    .sub{
        width:40vw;
        text-align: center;
        background-color: rgba(255, 255, 255, 0.333);
        
        padding-left: 20px;
        padding-right: 20px;
        padding-top: 0%;
        padding-bottom: 20px;
        font-family: Georgia, 'Times New Roman', Times, serif;

    }
    textarea{
        text-align: center;
        padding-top: 50px;
        padding-bottom: 50px;

    }
    .end{
        font-family: Georgia, 'Times New Roman', Times, serif;
        font-size: small;
        font-weight: 700;
        text-align: center;
        padding-top: 10px;
    }
</style>
<body >
    <div class="wait">
        <div class="background">
            <div class="main">
                <h1>CONTACT FORM</h1>
                <h3>Please fill all texts in the field</h3>
            </div>
            <div class="sub">
                <p >
                    <legend>YOUR NAME: </legend>
                    <input type="text" style="background-color: rgba(255, 255, 255, 0.525);" required>
                </p>
                <p>
                    <legend>E-MAIL:</legend>
                     <input type="email" name="email" id="email" style="background-color: rgba(255, 255, 255, 0.525);" required>
                    </p>
                <p>
                    <legend>MESSAGE:</legend>
                     <textarea name="enter your message" placeholder=" " cols="50" rows="5" style="background-color: rgba(255, 255, 255, 0.525);" required></textarea>
                </p>
                <p>
                    <legend>SUBJECT: </legend>
                    <input type="text" style="background-color: rgba(255, 255, 255, 0.525);" required >
                </p>
            </div>
            <div class="end">
                <input type="submit" value="save" style="background-color: rgba(255, 255, 255, 0.525);">
            </div>
        </div>

    </div>
    
    
</body>
</html>
