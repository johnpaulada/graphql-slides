---?image=images/bg-code.jpg&size=cover

![Logo](./images/gql-logo-256.png)

## GraphQL
##### A Practical Introduction
---
# GraphQL
<span style="color: #444">is a new API standard that provides a more efficient, powerful and flexible alternative to REST</span>
---
# API
<span style="color: #444">is an interface that allows you to use an application.</span>
+++
# REST
<span style="color: #444">is way of structuring a Web API.</span>
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
		"homeworld": "http://swapi.co/api/planets/1/",
		"films": [
			"http://swapi.co/api/films/2/",
			"http://swapi.co/api/films/6/",
			"http://swapi.co/api/films/3/",
			"http://swapi.co/api/films/1/",
			"http://swapi.co/api/films/7/"
		],
		"species": [
			"http://swapi.co/api/species/1/"
		],
		"vehicles": [
			"http://swapi.co/api/vehicles/14/",
			"http://swapi.co/api/vehicles/30/"
		],
		"starships": [
			"http://swapi.co/api/starships/12/",
			"http://swapi.co/api/starships/22/"
		],
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
@[10-39]
