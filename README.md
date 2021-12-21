var http = require("http");

http.createserver(function(req,res){
    res.write("Hello world and Hello Participants");
    res.end();
    console.log("this is a test");
    }).listen(8000)

    console.log ("Server running at port number 8000");