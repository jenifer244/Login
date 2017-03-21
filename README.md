
            <body>
                <div id="header">
                </div>
                    <div class="menu">
                        <ul>
                        <img src="AMA_University_logo.png">
                        <li class="menus menu-jenifer">JENIFER</li>
                        <li class="menus menu-jemy">JEMY</li>
                        <li class="menus menu-services">SERVICES</li>
                        <li class="menus menu-about">ABOUT US</li>
                        <li class="menus menu-home">HOME</li>
                        </ul>
                        
                    </div>
                        <div id="center">
                            <p>AMA &nbsp;SCHEDULING &nbsp; SYSTEM<br>for<br>Senior &nbsp;High</p>
                             <img src="3.png">


                             <button onclick="document.getElementById('stdbtn').style.display='block'" style="width:auto;" class="stdbutton"> Student</button>
                                <div id="stdbtn" class="BTN">
                                    <span onclick="document.getElementById('stdbtn').style.display='none'" class="cslose" title="CloseBTN">×</span>
                                        <form class="btn-content animate">
                                            <div class="SignUpForm">
                                                <label><b>&nbsp;&nbsp;&nbsp;&nbsp;USN &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</b></label>
                                                <input type="text" maxlength="11" placeholder="Enter USN" name="USN" required>
                                                <br>
                                                <label><b>Password &nbsp;</b></label>
                                                <input type="password" maxlength="15" placeholder="Enter Password" name="password" required>
                                                <br><br>
                                                <div class="clearfix">
                                                <button type="button" onclick="document.getElementById('stdbtn').style.display='none'" class="cancel"> Cancel </button>
                                                <button type="submit" class="login"> Log In </button>
                                                    </div>
                                            </div>
                                        </form>
                            
                        </div>

                            
                            
                                <script>
                                    // Get the modal
                                    var BTN = document.getElementById('stdbtn');

                                    // When the user clicks anywhere outside of the modal, close it
                                    window.onclick = function(event) {
                                        if (event.target == BTN) {
                                            BTN.style.display = "none";
                                        }
                                    }
                                </script>
                        
                                    <button onclick="document.getElementById('stdbtn').style.display='block'" style="width:auto;" class="admbtn"> Admin</button>
                                <div id="stdbtn" class="BTN">
                                    <span onclick="document.getElementById('stdbtn').style.display='none'" class="close" title="CloseBTN">×</span>
                                    
                                    
                                        <form class="btn-content animate">
                                            <div class="SignUpForm">
                                                <label><b>&nbsp;&nbsp;&nbsp;&nbsp;USN &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</b></label>
                                                <input type="text" maxlength="11" placeholder="Enter USN" name="USN" required>
                                                <br>
                                                <label><b>Password &nbsp;</b></label>
                                                <input type="password" maxlength="15" placeholder="Enter Password" name="password" required>
                                                <br><br>
                                                <div class="clearfix">
                                                <button type="button" onclick="document.getElementById('stdbtn').style.display='none'" class="cancel"> Cancel </button>
                                                <button type="submit" class="login"> Log In </button>
                                                    </div>
                                            </div>
                                        </form>
                                </div>
                            
                            
                                <script>
                                    // Get the modal
                                    var BTN = document.getElementById('stdbtn');

                                    // When the user clicks anywhere outside of the modal, close it
                                    window.onclick = function(event) {
                                        if (event.target == BTN) {
                                            BTN.style.display = "none";
                                        }
                                    }
                                </script>
                           
                        </div>
                <div class="bgtwo">
                </div>
                
                <footer>
                    <div id="foot">
                        <p id="c_right">@copyright_2017</p>
                    </div>
                </footer>
                
                <style>
                *{
    padding: 0px;
    margin: 0px;
    border: 0px;
    outline: none;
}

#header{
    background-color: #283f59;
    height: 25px;
    width: 100%;
    opacity: 0.9;
}

.menu{
    background-color: white;
    height: 60px;
    width: 100%;

}

.menus{
    font-family: 'Questrial', sans-serif;
    padding-right: 10px;
    margin-top: 20px;
    margin-right: 30px;
    font-size: 17px;
    cursor: pointer;
    background-color: white;
    color: black;
}

.menu-jenifer:hover{
    color: #4CAF50;
    font-weight: bold;
}

.menu-jemy:hover{
     color: #4CAF50;
    font-weight: bold;
}

.menu-services:hover{
     color: #4CAF50;
    font-weight: bold;
}

.menu-about:hover{
     color: #4CAF50;
    font-weight: bold;
}

.menu-home:hover{
     color: #4CAF50;
    font-weight: bold;
}

.menu img{
    height: 50px;
    width: 115px;
    padding-top: 5px;
    padding-left: 150px;
    
}

li{ /* menu list */
    list-style: none;
    display: inline;
    float: right;
}

p{ /* sa title part */
    position: absolute; 
    margin-top: 130px;
    left: 450px;
    text-align: center;
    color: white;
    font-size: 40px;
    font-family: 'Monoton', cursive;
}

#center {
    position: relative;
    width: 100%;    
}
}
.button{ /* para sa button nga tag */
    background-color: transparent; 
    border: none;
    color: white;
    padding: 5px 20px;
    text-align: center;
    text-decoration: none;
    font-size: 14px;
    border-radius: 4px;
    font-family: 'Hind', sans-serif;
    font-size: 20px;
}

.stdbtn{ /*para sa student button kasabot?! */
    margin-top: 350px;
    margin-left: 550px;
    display: inline-block;
    border: 2px solid #4CAF50;
    color: black;
}

.admbtn{ /* para sa admin button ay sig binogo! */
    top: 350px;
    left: 700px;
    border: 2px solid #4CAF50;
    
}

.stdbtn:hover { /*hover sa student button */
    background-color:#4CAF50;
    color: white;
}

.admbtn:hover{ /*hover sa admin button */
    background-color:#4CAF50;
    color: white;
}



a{
    text-decoration: none;
    color: white;
}

#center img{ /* background image ni bayyeeeet! */
    height: 450px;
    width: 100%;
}

footer{
    background-color: #223d55;
    height: 60px;
    width: 100%;
}

#foot{
     background-color: #283f59;
     height: 20px;
     width: 100%;
     position: absolute;
     margin-top: 66px;
    
}
#c_right{
    color:white;
    font-family: 'Petit Formal Script', cursive;
    padding-left: 630px;
    font-size: 10px;
    padding-top: 3px;
    
}
</style>
            </body
            
            
            
