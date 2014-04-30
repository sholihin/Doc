``` javascript
var strRadio = '';
strRadio  = strRadio + '<div id="xx">';
 
for(var i=0; i<data.options.length; i++){
        strRadio = strRadio + '<input type="radio" id="'+data.options[i].id+'" value="'+data.options[i].value+'">';
}
 
strRadio  = strRadio + '</div> ';
 
$('#id_div').append(strRadio);
```
