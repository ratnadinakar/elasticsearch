# Elastic Search Snippets

###Getting total records

```
Request Type : GET
URL : http://elasticsearch/index/_count

```

###Including Regular Expression

Basic Structure

```
Request Type : POST
URL : http://elasticsearch/index/_search

Body
{
   "query":{
      "regexp":{
       "property":"regularExpression"
      }
   }
}

```

