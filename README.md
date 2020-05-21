# Simple_CRUD_API_SQLITE3

<p>Simple CRUD API  Build With  <a href="https://www.tornadoweb.org/en/stable/">Tornado</a>  Framework And SQLite3  For The Database</p>
<hr>
<h1>#setup:</h1>
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
<tr>
  <td>
    6) run project with <a href="https://pypi.org/project/torn/">torn cli</a> : <b>#command: [ torn run ] </b>  </td>
 </tr>
</table>
<hr>
<h3>#Use <a href="https://www.postman.com/">postman</a> to send requests to <a href="http://localhost:8000">http://localhost:8000</a> </h3>
<br>
<table>
  <tr>
    <td>
<img src="https://github.com/MedAmineFouzai/Simple_CRUD_API_SQLITE3/blob/master/Captures/Capture.PNG">
</td>
<tr>
<table>
 <hr>
  <h1>#Also use methods [Delete,Put,GET]:</h1>
  
<hr>
<h2>ex:[GET]</h2>
  
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
   
 <h2>ex:[DELETE]</h2>
    
      {
      "id":"0001"
      }
 
 <h2>ex:[PUT]</h2>
    
    {
    "id":"0001",
    "title":"Title of POST 1 UPDATED",
    "body":"Body of POST 1 UPDATED",
    }
  
  
