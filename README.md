## api-Movies-info

# • Example of an API
```
GAT : https://www.omdbapi.com/?apikey=f2e5b1fc&s={text}
```
# • Example
```
import requests
# code by ruks
x =input("Enter the name of the movie")

response = requests.get("https://www.omdbapi.com/?apikey=f2e5b1fc&s="+x).json()

print(response)
```
# • The result
```
{"Search":[{"Title":"Pirates of the Caribbean: The Curse of the Black Pearl","Year":"2003","imdbID":"tt0325980","Type":"movie","Poster":"https://m.media-amazon.com/images/M/MV5BNGYyZGM5MGMtYTY2Ni00M2Y1LWIzNjQtYWUzM2VlNGVhMDNhXkEyXkFqcGdeQXVyMTMxODk2OTU@._V1_SX300.jpg"},{"Title":"Black Swan","Year":"2010","imdbID":"tt0947798","Type":"movie","Poster":"https://m.media-amazon.com/images/M/MV5BNzY2NzI4OTE5MF5BMl5BanBnXkFtZTcwMjMyNDY4Mw@@._V1_SX300.jpg"},{"Title":"Black Panther","Year":"2018","imdbID":"tt1825683","Type":"movie","Poster":"https://m.media-amazon.com/images/M/MV5BMTg1MTY2MjYzNV5BMl5BanBnXkFtZTgwMTc4NTMwNDI@._V1_SX300.jpg"},{"Title":"Men in Black","Year":"1997","imdbID":"tt0119654","Type":"movie","Poster":"https://m.media-amazon.com/images/M/MV5BOTlhYTVkMDktYzIyNC00NzlkLTlmN2ItOGEyMWQ4OTA2NDdmXkEyXkFqcGdeQXVyNTAyODkwOQ@@._V1_SX300.jpg"},{"Title":"Black Mirror","Year":"2011–","imdbID":"tt2085059","Type":"series","Poster":"https://m.media-amazon.com/images/M/MV5BYTM3YWVhMDMtNjczMy00NGEyLWJhZDctYjNhMTRkNDE0ZTI1XkEyXkFqcGdeQXVyMTkxNjUyNQ@@._V1_SX300.jpg"},{"Title":"Black Hawk Down","Year":"2001","imdbID":"tt0265086","Type":"movie","Poster":"https://m.media-amazon.com/images/M/MV5BYWMwMzQxZjQtODM1YS00YmFiLTk1YjQtNzNiYWY1MDE4NTdiXkEyXkFqcGdeQXVyNDYyMDk5MTU@._V1_SX300.jpg"},{"Title":"Men in Black II","Year":"2002","imdbID":"tt0120912","Type":"movie","Poster":"https://m.media-amazon.com/images/M/MV5BMTMxNDA0NTMxMV5BMl5BanBnXkFtZTYwMDE2NzY2._V1_SX300.jpg"},{"Title":"Men in Black 3","Year":"2012","imdbID":"tt1409024","Type":"movie","Poster":"https://m.media-amazon.com/images/M/MV5BMTU2NTYxODcwMF5BMl5BanBnXkFtZTcwNDk1NDY0Nw@@._V1_SX300.jpg"},{"Title":"Orange Is the New Black","Year":"2013–2019","imdbID":"tt2372162","Type":"series","Poster":"https://m.media-amazon.com/images/M/MV5BYjYyM2FmMmMtZDgyZi00NGU3LWI3NzktODllZDY0YzQyNzgyXkEyXkFqcGdeQXVyMTkxNjUyNQ@@._V1_SX300.jpg"},{"Title":"Pitch Black","Year":"2000","imdbID":"tt0134847","Type":"movie","Poster":"https://m.media-amazon.com/images/M/MV5BNTNmYzE1OWYtZDdjNC00OTdhLTg1YjUtYWJlZTVkMzkzNmVkXkEyXkFqcGdeQXVyMTQxNzMzNDI@._V1_SX300.jpg"}],"totalResults":"5792","Response":"True"}
```
