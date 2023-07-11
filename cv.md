# Name
* Alexander
# Surname
* Gyurov 
# Age
* 32
## Contact 
* +7 906 033 99 19
## Personal information 
* _Encouraging account manager with a sound experience in nuclear, aviation and heavy machinery areas. Analytical problem-solver with talents for team building, motivation and thinking outside the box._
### Skills 
* _JavaScript (Node.js)_, _C++_, _SQL_, _MongoDB_, _TypeScript_
### SampleCode
`//ejs Java script engine... 
// add views folder, make profile view with extention ejs 
//and take parameters and look how to 
//insert them on ejs website frame

var express = require ('express');

var app = express();

var bodyParser = require('body-parser')

var urlencodedParser = bodyParser.urlencoded({ extended: false })

 app.set('view engine', 'ejs');
app.use('/my-first-javascript',express.static('my-first-javascript'));

app.get('/',function (req,res){

	res.render('index');
	console.log ('request was made : '+ req.url);
});

app.get('/contact',function (req,res){
	
	res.render('contact', {qs:req.query});
	
});
//body parsers 17 02 23
app.post('/contact',urlencodedParser,function (req,res){
	console.log (req.body);
	res.render('contact-success', {data: req.body});
	
});

app.get('/profile/:name',function (req,res){
var data = {age:32, job: "jobless", hobbies: ['fishing','snorkling','titfucking']}
	res.render('profile', {person: req.params.name, data:data});

	console.log ('request was made : '+ req.url);
});

app.listen(3000);` 

#### Experience
* _No experience in coding_

#### Education
* _State University of Management (Moscow, Russia)_

##### Courses
* _Programming in blockchain (Solidity) - Moscow Coding School- 2018_
* _CPP advanced course - Coursera - 2020_
* _Java Script course - Codeacademy - 2022_
* _Type Script course - Ninja Youtube -2023_ 

##### Languages
* _English - C1_
* _Spanish - B1_
* _Bulgarian - A2_
* _Russian - C2_

###### Photo
!(C:\Users\Alexandr\YandexDisk\Photo_CV\CHEK7083 small.jpg)
