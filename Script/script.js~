$(document).ready(function(){
$(".grid").hide();
$(".but").click(function(){
$(".grid").empty();
$(".grid").fadeIn(3000);
var size = prompt("Enter size");
var dimensions=450/size;
for(var i=1;i<=size*size;i++){
$(".grid").append('<div class="box"></div>');
}
$(".box").css("width",dimensions);
$(".box").css("height",dimensions);
});
var color="black";
$(".erase").click(function(){
color="white";
});
$(document).on("mouseover",".box",function(){
$(this).css("background-color",color);
});
});
