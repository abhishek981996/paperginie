# Paperginie

An restful API made for svnit college students to collect information of subjects and previous year question paper.


## Making Restful calls 

Example 1:
  make a request to api using request module of python.
  ```sh
object = requests.get("http://45.55.215.199/papergenie/paper/rollno")
json object = object.text()


```

This will return a json object in following format

```sh
{
  {
  id :1
  subject:ce
  papar:app/paper_name.pdf
  }
}

```

The paper url can be obtained simply by adding the path to the base url
```
BASE_URL:http://45.55.215.199/
```

## More to be updated
