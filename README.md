$("id").keydown(function(e){ 
switch(e.which) { 
case 38: // up 
break; 

case 40: // down 
break; 

default: return; // exit this handler for other keys 
} 
e.preventDefault(); 
});
