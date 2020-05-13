# Simple_CRUD_API_SQLITE3

<p>Simple CRUD API  Useing Tornado  Framework And SQLite3  For The Database</p>
<hr>
<h1>#setup:</h1>
<hr>
<table>
<tr>
<td> 1)  git clone https://github.com/MedAmineFouzai/Simple_CRUD_API_SQLITE3 </td>
</tr>
<tr>
<td> 2) cd Simple_CRUD_API_SQLITE3</td>
</tr>
<tr>
<td> 3) pip install pipenv</td>
</tr>
</tr>
<td> 4) pipenv --python 3.6</td>
</tr>
<tr>
<td> 5) pipenv install - r requirements.txt</td>
</tr>
</table>
<hr>
<h2>-then run project with torn cli :</h2>
<h1>#command: [ torn run ] </h1>
<p1>-use postman to send request to [ http://localhost:8000/ ]</p1>
<table>
  <tr>
    <td>
<img src="https://github.com/MedAmineFouzai/Simple_CRUD_API_SQLITE3/blob/master/Captures/Capture.PNG">
</td>
<tr>
<table>
 <hr>
  <h1>Also use methods [Delete,Put,GET]:</h1>
  
<hr>
<h2>ex:[POST]</h2>
-request[body]:
  {
  
    "id":"0001",
    "title":"POST 1",
    "body":"this is POST 1",
    
    "id":"0002",
    "title":"POST 2",
    "body":"this is POST 3"
    
    "id":"0003",
    "title":"POST 3",
    "body":"this is POST 4"
   }
-response:
{
[
[1, "POST 2", "this is POST 1"],
[2, "POST 3", "this is POST 2"],
[3, "POST 4", "this is POST 3"]
]
}
  

  
  
  
