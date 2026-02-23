library(nortest)

movies <- read.csv("Movies_2026.csv")

head(movies
, 5)

# Actors y Actors characters van aqui
cual_nominales <- c(
  "genres",
  "homePage",
  "productionCompany",
  "productionCompanyCountry",
  "productionCountry",
  "video",
  "director",
  "originalTitle",
  "title",
  "originalLanguage"
)

cual_ordinales <- c(
  "releaseDate"
)

cuant_discretas <- c(
  "budget",
  "revenue",
  "runtime",
  "voteAvg",
  "voteCount",
  "genresAmount",
  "productionCoAmount",
  "productionCountriesAmount",
  "actorsAmount",
  "castWomenAmount",
  "castMenAmount",
  "releaseYear"
)


# actors popularity va en cauantitativo de continuas
cuant_continuas <- c(
  "popularity"
)

cuantitativas <- c(cuant_discretas, cuant_continuas)
cuantitativas
datos_cuant <- movies[, cuantitativas]
head(datos_cuant, 5)

cualitativas <- c(cual_nominales, cual_ordinales)
cualitativas
datos_cual <- movies[, cualitativas]
head(datos_cual, 5)
