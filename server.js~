var app=require('express')();

app.get('/',function(req,res){
	res.sendFile(__dirname+'/quote.html');
});

var port = process.env.PORT || 8081;

var server=app.listen(port,function(request,response){
    console.log("Catch the action at http://localhost:"+port);
});
