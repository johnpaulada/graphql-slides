---?image=images/bg-code.jpg&size=cover

![Logo](./images/gql-logo-256.png)

## GraphQL
##### A Practical Introduction

---
# GraphQL
<span style="color: #777">*is a new API standard that provides a more efficient, powerful and flexible alternative to REST*</span>

---
# GraphQL
<span style="color: #777">*a query language for APIs - not databases.*</span>

---
### Practical Definition of Terms

+++
# API
<span style="color: #777">is an interface that allows you to use an application.</span>

+++
# REST
<span style="color: #777">is way of structuring a Web API.</span>

+++
### Star Wars REST Example

```
Request:
GET /people

Response:
{
  "count": 1
  "next": "",
  "previous": null,
  "results": [{
    "name": "Luke Skywalker",
		"height": "172",
		"mass": "77",
		"hair_color": "blond",
		"skin_color": "fair",
		"eye_color": "blue",
		"birth_year": "19BBY",
		"gender": "male",
    ...
		"created": "2014-12-09T13:50:51.644000Z",
		"edited": "2014-12-20T21:17:56.891000Z",
		"url": "http://swapi.co/api/people/1/"
	}]
}
```
@[1-2]
@[4]
@[6]
@[7]
@[8]
@[9]
@[10-21]

+++
### Star Wars REST Example

```
Request:
GET /people/1

Response:
{
  "name": "Luke Skywalker",
  "height": "172",
  "mass": "77",
  "hair_color": "blond",
  "skin_color": "fair",
  "eye_color": "blue",
  "birth_year": "19BBY",
  "gender": "male",
  ...
  "created": "2014-12-09T13:50:51.644000Z",
  "edited": "2014-12-20T21:17:56.891000Z",
  "url": "http://swapi.co/api/people/1/"
}
```

@[1-2]
@[4]
@[6-17]

---
### A Better Alternative to REST
- Efficient   |
- Flexible    |
- Easy to use |

+++
### GraphQL is **EFFICIENT**
<p class="fragment" style="color: #777">GraphQL allows the API consumers to just get what they need, which makes it more efficient than REST when mobile data is limited and/or the connectivity is weak.</p>

+++
### GraphQL is **FLEXIBLE**
<p class="fragment" style="color: #777">Because GraphQL allows API consumers to just get the data they need, it can be used by any client, no matter what the framework or platform.</p>

+++
### GraphQL is **EASY TO USE**
<p class="fragment" style="color: #777">With changes in API specifications, REST APIs might need to change drastically, too. GraphQL allows faster modification and creates a predictable API allowing for rapid development.</p>
