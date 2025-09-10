# my-first-repo
For Lab1 - Web-Apss
Chetan kumar, and I would like to visit Japan someday
Change for Assignment 1

***
### Breaking Bad best Actors and best TV shows (best to least-best)

1. Aaron Paul
2. Bryan Cranston
3. Dean Norris
* The mentalist 
* The 100
* Mindhunter

**[activity_page](MyActivity.md)**

***
### Men I Would Like To Meet

There is always a desire for anyone to meet your favorite people, idols or just favorite actors. These are just some of my favorite people ( deceased ) for me. Many reasons, main being their philophsies 

| Names | Reason | Birthday | Deceased Date |
| ---   | ---    | ---      | ---           |
| Ratan Tata | Indian Billionare who donated almost all of his $100b wealth | Dec 28, 1938 | Oct 9, 2024 | 
| Confucious | Chineese Philospher known for his religion "lifestyle" | Unknown | 479 BC |
| Shane Warne | Best Cricketer/bowler ever in the history of cricket | Sep 13, 1969 | Mar 4, 2022 | 
| Christopher Nolan | World's best director especially the sci-fi ones | Jul 30, 1970 | N/A |

***

### Favorite Quotes 

> You have to dream before your dreams can come true
*-Dr A.P.J Abdul Kalam* <br>

> Man needs his difficulties because they are necessary to enjoy success
*-Dr A.P.J Abdul Kalam*

***

### Typescript function composition

The following program combines functions from left to right to give out a new function

```
const compose = (...fns: Func[]) => {
	fns.reduce((f, g) => (...args: any[]) => f(...castArray(g(...args))));
}
```

[Code Link](https://shared.code.pieces.app/?compressed=eyJiYXNlIjoiaHR0cHM6Ly90eXBlc2NyaXB0LnBpZWNlcy5jbG91ZCIsInNoYXJlIjoiNmE1MDhmNzgtOTZjZC00NWQ1LTliMDMtY2I3NzdkYThhMjQ2IiwiYXNzZXQiOiI2Y2Q3ODkxMS02YzMyLTQyNDgtODJjMi05YzM3NDYyNDZmZmIiLCJuYW1lIjoiUGllY2VzIFRlYW0iLCJ0aXRsZSI6IkZ1bmN0aW9uIGNvbXBvc2l0aW9uIiwiZGVzY3JpcHRpb24iOiJQZXJmb3JtcyBsZWZ0IHRvIHJpZ2h0IGZ1bmN0aW9uIGNvbXBvc2l0aW9uLiBGcm9tIFRoZSBQaWVjZXMgVHlwZVNjcmlwdCBDb2xsZWN0aW9uLiIsInVzZXIiOnsic2NoZW1hIjp7Im1pZ3JhdGlvbiI6Niwic2VtYW50aWMiOiJNQUpPUl8wX01JTk9SXzBfUEFUQ0hfMSJ9LCJwaWN0dXJlIjoiaHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2pnaUFUZmM3S3YxUzFyaW5QZmZKX2Z0ZnVOLXI2Vk1PUk5JTWdzPXM5Ni1jIiwiZW1haWwiOiJ0eXBlc2NyaXB0LmNvbGxlY3Rpb25AcGllY2VzLmFwcCIsImNyZWF0ZWQiOnsidmFsdWUiOiIyMDIyLTA2LTIzVDE4OjQxOjA2LjQ1OVoiLCJyZWFkYWJsZSI6IjMgeWVhcnMgYWdvIn0sInVwZGF0ZWQiOnsidmFsdWUiOiIyMDIyLTA2LTIzVDE4OjQxOjQyLjY0NVoiLCJyZWFkYWJsZSI6IjMgeWVhcnMgYWdvIn0sImlkIjoiODdjZjEzYzgtMGM5NS00YWQ0LTkyMGEtZDBlNDBhMTQ5NGZjIiwibmFtZSI6IlBpZWNlcyBUZWFtIiwiYWVzdGhldGljcyI6eyJ0aGVtZSI6eyJkYXJrIjp0cnVlfSwiZm9udCI6eyJzaXplIjoxNn19LCJhbGxvY2F0aW9uIjp7InNjaGVtYSI6eyJtaWdyYXRpb24iOjYsInNlbWFudGljIjoiTUFKT1JfMF9NSU5PUl8wX1BBVENIXzEifSwiaWQiOiI4N2NmMTNjOC0wYzk1LTRhZDQtOTIwYS1kMGU0MGExNDk0ZmMiLCJ1c2VyIjoiODdjZjEzYzgtMGM5NS00YWQ0LTkyMGEtZDBlNDBhMTQ5NGZjIiwidXJscyI6eyJiYXNlIjp7InN0YXR1cyI6IlJVTk5JTkciLCJ1cmwiOiJodHRwczovL3VzZXItODdjZjEzYzgtMGM5NS00YWQ0LTkyMGEtZDBlNDBhMTQ5NGZjLWZoY21iaGVrbHEtdWMuYS5ydW4uYXBwIn0sImlkIjp7InN0YXR1cyI6IlJVTk5JTkciLCJ1cmwiOiJodHRwczovLzg3Y2YxM2M4LTBjOTUtNGFkNC05MjBhLWQwZTQwYTE0OTRmYy5waWVjZXMuY2xvdWQifSwidmFuaXR5Ijp7InN0YXR1cyI6IlJVTk5JTkciLCJ1cmwiOiJodHRwczovL3R5cGVzY3JpcHQucGllY2VzLmNsb3VkIn19LCJzdGF0dXMiOnsiY2xvdWQiOiJSVU5OSU5HIn0sInByb2plY3QiOiJydW50aW1lLXVzZXItY2xvdWQtZ3JvdXAtMCIsInVwZGF0ZWQiOnsidmFsdWUiOiIyMDIyLTA2LTIzVDE4OjQyOjEyLjg3NTU5MVoiLCJyZWFkYWJsZSI6IjMgeWVhcnMgYWdvIn0sInZlcnNpb24iOiIzLjEuMCJ9LCJhcGlLZXlzIjpbXX19&user=87cf13c8-0c95-4ad4-920a-d0e40a1494fc)