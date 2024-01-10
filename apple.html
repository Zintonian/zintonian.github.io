<HTML>
    <head>
        <title>Incremental Game</title>

        <style>
           .sectionLeft {
            float: left;
            width: 80%;
           }
           .sectionRight {
            float: right;
            width: 20%;
           }
           .scoreContainer {
            background-color: rgb(red, green, blue);
            width: 50%;
            padding: 10px;
            border-radius: 50px;
            font-size: 24px;
            font-weight: bold;
           }

           .clickerContainer img {
            position: relative;
            transition: all 0.2s ease-in-out
           }

           .clickerContainer img:hover {transform: scale(1.1);}
           .clickerContainer img:active {transform: scale(0.99)}

           .shopButton {
            background-color: rgb(90, 200, 80);
            transition: all .2s ease-in-out;
            border-radius: 50px;
            width: 100%;
            margin: 10px 0px 10px 0px;
           }
           .shopButton:hover {
            background-color: rgb(60, 170, 50);
            transition: all .2s ease-in-out;
           }
           .shopButton #nameAndCost p {
            margin: 20px;
            width: 60%;
           }
           .shopButton #nameAndCost p:first-of-type {
            font-size: 24px;
           }
           .shopButton #amount {
            font-size: 36px;
            font-family: staliches;
            width: 15%;
           }
        </style>
    </head>

    <body>
        <div class="sectionLeft">
            <center>
            <div class="scoreContainer">
                <p>Leaves: <span id="score"></span></p>
                <p>Leaves Per Click: <span id="clickingPower"></span></p>
                <p>Trees: <span id="tree"></span></p>
            </div>
            <div class="clickerContainer">
                <img src="Images/Copy of Parts & Types of Trees for Education Infographics by Slidesgo.jpg" height="256px" width="512px" onclick="addToScore()">
            </div>
            </center>
        </div>
        <div class="sectionRight">
            <table class="shopButton" onclick="buyUpgrade1()">
                <tr>
                    <td id="nameAndCost">
                        <p>Healthier Trees</p>
                        <p><span id="upgrade1Cost">35</span> Leaves</p>
                    </td>
                    <td id="amount"><span id="upgrade1Amount">0</span>

                    </td>
                </tr>
            </table>
            <table class="shopButton" onclick="buyUpgrade2()">
                <tr>
                    <td id="nameAndCost">
                        <p>Mutate Trees</p>
                        <p><span id="upgrade2Cost">250000</span> Leaves</p>
                    </td>
                    <td id="amount"><span id="upgrade2Amount">0</span>

                    </td>
                </tr>
            </table>
            <table class="shopButton" onclick="Prestige1()">
                <tr>
                    <td id="nameAndCost">
                        <p>Prestige For Trees</p>
                        <p><span id="Prestige1Req">10000000000</span> Leaves</p>
                    </td>
                    <td id="amount"><span id="tree">0</span>

                    </td>
                </tr>
            </table>
        </div>
        <script>
            var score = 0;
            var tree = 1;
            var upgrade1Cost = 35;
            var upgrade1Amount = 0;
            var upgrade2Cost = 250000;
            var upgrade2Amount = 0;
            var Prestige1Req = 1000000000
            var clickingPower = 1;
            function buyUpgrade1 () {
                if (score >= upgrade1Cost) {
                    score = score - upgrade1Cost;
                    upgrade1Amount = upgrade1Amount + 1;
                    upgrade1Cost = Math.round(Math.pow(upgrade1Cost,1.035));

                    document.getElementById("score").innerHTML = score;
                    document.getElementById("upgrade1Amount").innerHTML = upgrade1Amount;
                    document.getElementById("upgrade1Cost").innerHTML = upgrade1Cost; 
                }
            }
            function buyUpgrade2 () {
                if (score >= upgrade2Cost) {
                    score = score - upgrade2Cost;
                    upgrade2Amount = upgrade2Amount + 1;
                    upgrade2Cost = Math.round(Math.pow(upgrade2Cost,1.25)*5);

                    document.getElementById("score").innerHTML = score;
                    document.getElementById("upgrade2Amount").innerHTML = upgrade2Amount;
                    document.getElementById("upgrade2Cost").innerHTML = upgrade2Cost; 
                }
            }
            function Prestige1 () {
                if (score >= Prestige1Req) {
                    tree = tree + Math.round(Math.log10(score) - 8)
                    score = 0;
                    upgrade1Amount = 0;
                    upgrade1Cost = 35;
                    upgrade2Amount = 0;
                    upgrade2Cost = 250000
                    Prestige1Req = Prestige1Req * 10
                    document.getElementById("score").innerHTML = score;
                    document.getElementById("upgrade1Amount").innerHTML = upgrade1Amount;
                    document.getElementById("upgrade1Cost").innerHTML = upgrade1Cost;
                    document.getElementById("upgrade2Amount").innerHTML = upgrade2Amount;
                    document.getElementById("upgrade2Cost").innerHTML = upgrade2Cost;
                    
                }
            }
            function addToScore() {
                clickingPower = Math.round(1 + (Math.pow(upgrade1Amount, 1 + 0.25 * upgrade2Amount)) * Math.pow(Math.pow(upgrade1Amount, 1 + 0.25 * upgrade2Amount),1.2) *(1 + 4 * upgrade2Amount) * Math.pow(tree, 2));
                score += clickingPower;
                document.getElementById("score").innerHTML = score;
                document.getElementById("clickingPower").innerHTML = clickingPower;
                document.getElementById("tree").innerHTML = tree 
            }
            setInterval(function() {
                score = score + 0;
                document.getElementById("score").innerHTML = score;               
            }, 100);
            document.title = "Leaves - Leave Cosmos";

        </script>
    </body>
</HTML>
