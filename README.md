setInterval(function() { Game.ClickCookie(); }, 250);

var autoGoldenCookie = setInterval(function() { for (var h in Game.shimmers){if(Game.shimmers[h].type=="golden"){Game.shimmers[h].pop();}} }, 1500);
