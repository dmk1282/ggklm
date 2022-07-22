setInterval(function() { Game.ClickCookie(); }, 250);

var autoGoldenCookie = setInterval(function() { for (var h in Game.shimmers){if(Game.shimmers[h].type=="golden"){Game.shimmers[h].pop();}} }, 1500);




javascript:(function()%7BsetInterval(function()%20%7B%20Game.ClickCookie()%3B%20%7D%2C%20250)%7D)()


javascript:(function()%7Bvar%20autoGoldenCookie%20%3D%20setInterval(function()%20%7B%20for%20(var%20h%20in%20Game.shimmers)%7Bif(Game.shimmers%5Bh%5D.type%3D%3D%22golden%22)%7BGame.shimmers%5Bh%5D.pop()%3B%7D%7D%20%7D%2C%201500)%7D)()
