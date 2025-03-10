# Respuestas de la TAREA:

### API Imbd:

1. 10
2. "Aqua Teen Hunger Force Colon Movie Film for Theaters"
3. ImdbVotes: "1,017,055", Actors: "Billy Crystal, John Goodman, Mary Gibbs", https://m.media-amazon.com/images/M/MV5BMTY1NTI0ODUyOF5BMl5BanBnXkFtZTgwNTEyNjQ0MDE@._V1_SX300.jpg
4. "Genre": "Drama, Sport", "Director": "Sylvester Stallone", "Runtime": "91 min",
5. "Title": "Willy Wonka & the Chocolate Factory",   "Year": "1971"

### API Pokeapi:

1. Speed: 90, Defense 40, attack 55, hp 35, special-attack 50, special-defense 50, weight 60, height 4
2. "count": 21
3. Mewtwo
4. mega-punch
5. "height": 7, "weight": 69

# Mi procedimiento:

Lo que hice fue investigar cómo acceder a los datos en cada una de las APIs. En la de Imbd siempre tenias que poner la apiKey para que funcione, y después pedirle los datos, por eso, los parametros siempre se veían asi http://www.omdbapi.com/?apikey=fee9f9ae, y luego se le sumaba con un & lo que uno queria buscar. 
Después para buscar en la Api de Pokeapi siempre mantenías este parámetro de base https://pokeapi.co/api/v2/, y depende lo que querías buscar le agregabas algo (en este caso nunca usas la &). Por ejemplo, para buscar todos los tipos de pokemones escribis type después del v2/. 

# Problemas que tuve:

Uno problema que tuve fue encontrar todos los datos de Pikachu en la Api de Pokeapi, pero despues de investigar, me di cuenta que "base_stat": se refería a la cantidad del atributo que posee el pokemon, y el atributo se definia en el campo de  "name":.
