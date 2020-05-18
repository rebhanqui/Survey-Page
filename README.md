# Survey-Page
Basic Survey Page

<!DOCTYPE HTML>
<html>

<head>
    <meta charset="lang-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Survey Form</title>
    <link rel="stylesheet" type="text/css"
        href="C://Users/Rebekah Quinn/Documents/Studio Ninty/Studio Ninty Online/HTML/survey-page.css">
    <link href="https://fonts.googleapis.com/css2?family=Inconsolata:wght@300&display=swap" rel="stylesheet">
</head>

<body>
    <div id="page-wrap">
            <form id="survey-form">
                <div class="header">
                    <h1 id="title">Survey Form</h1>
                    <p id="description">Thanks for taking the time to help us build more feautures in ACNH</p>
                </div>
        <content>
            <div class="form-group">
                <div class="name"> 
                    <label for="name" id="name-label" >
                        <h2>Name</h2>
                    </label>
                    <input type="text" required name="name" id="name" placeholder="Tom Nook" >
                </div>
                <div class="email">
                    <label for="email" id="email-label">
                        <h2>Email</h2>
                    </label>
                    <input type="email" required name="email" id="email" placeholder="nook@island.life">
                </div>

                <div class="location-options">
                    <label for="southern-hemisphere">
                        <h2 id="hemisphere">What Hemisphere are you Located in?</h2>
                        <input type="radio" required value="southern" name="southern-hemisphere-nothern-hemisphere" checked>Southern
                        Hemisphere
                    </label>
                    <br>
                    <label id="northern-hemisphere">
                        <input type="radio" required value="northern" name="southern-hemisphere-nothern-hemisphere">Northern Hemisphere</label>
                </div>
                
                <div id="dropdown">
                    <label for="island-fruit" id="fruit-heading">
                        <h2>What is your Native Fruit?</h2>
                    </label>

                    <select id="island-fruit" placeholder="Native Fruit">
                        <option id="cherry" value="1">Cherry</option>
                        <option id="apple" value="2">Apple</option>
                        <option id="orange" value="3">Orange</option>
                        <option id="pear" value="4">Pear</option>
                        <option id="peach" value="5">Peach</option>
                    </select>
                </div>
                <label for="play-start" id="date-label">
                    <h2 id="date">When did you start playing Animal Crossing New Horizons?</h2>
                    <input type="date" id="number-days" name="play-start-date"
                        placeholder="When did you start playing ACNH?">

                </label>

                <label for="number-label" id="number-label" placeholder="Bells Amount">
                    <h2>How many Bells do you currently have?</h2>
                    <input type="number" required id="number" name="bells" min="0" max="9999999" placeholder="Bells Amount">
                </label>

                <div class="comments">
                    <h2 id="further-comments">Tell us what your ideas and hopes are!</h2>
                    <label id="comments">
                        <textarea id="text-box" name="txtArea" rows="5" cols="50" style="align-self: center;"
                            placeholder="What would you like to see in upcoming ACNH Updates?"></textarea>
                    </label>
                </div>
            </div>
            <div class="good-bad-experience">
            <h2 id="experience-title">How has your ACNH experience been so far?</h2>
            <label for="game-likes" value="like-or-dislike">
                <input type="checkbox" id="disike" name="dislike" value="-2">Dislike</label>
                
                <input type="checkbox" id="meh" name="meh" value="-1">Meh</label>

                <input type="checkbox" id="okay" name="okay" value="0">Okay</label>

                <input type="checkbox" id="good" name="good" value="1">Good</label>

                <input type="checkbox" id="great" name="great" value="2">Great</label>
               </div> 
            </form>
            <div class="send-button">
                <button id="submit" type="submit">Send</button>
            </div>
    </div>

    </content>
    </div>
</body>

</html>
