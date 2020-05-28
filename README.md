# Simple_CRUD_API_SQLITE3

Simple CRUD API  Build With [Tornado](https://www.tornadoweb.org/en/stable/)  Framework And SQLite3  For The Database

-----------------------------

# setup:

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

## Use [Postman](https://www.postman.com/) to send requests to http://localhost:8000

 ----------------------------------------------
 
## Also use methods [Delete,Put,GET]:
  
-----------------------------------------------

## ex:[ GET ]
  
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
   
 ## ex:[ DELETE ]
    
      {
      "id":"0001"
      }
 
 ## ex:[ PUT ]
    
    {
    "id":"0001",
    "title":"Title of POST 1 UPDATED",
    "body":"Body of POST 1 UPDATED",
    }
  
  
