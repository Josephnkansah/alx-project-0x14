# alx-project-0x14

## API Overview  
The **MoviesDatabase API** allows developers to access a large database of movies and TV shows. It provides features like searching for titles, getting details about movies or actors, listing genres, finding top-rated or popular titles, getting reviews and trailers, and exploring similar content.

## Version  
**v2**

## Available Endpoints  

| Endpoint | Description |
| -------- | ------------ |
| `/titles` | Search for movies, TV shows, or short films using filters like title name, year, or genre. |
| `/titles/{titleId}` | Get detailed info about a specific title using its unique ID. |
| `/titles/x/upcoming` | Get a list of upcoming movies. |
| `/titles/x/top-rated` | Get a list of top-rated movies. |
| `/titles/x/popular` | Get a list of popular movies and shows. |
| `/actors` | Search for actors by name or get details for a specific actor. |
| `/genres` | List all available genres. |
| `/titles/{titleId}/similar` | Get similar movies or shows. |
| `/titles/{titleId}/reviews` | Get reviews for a specific title. |
| `/titles/{titleId}/videos` | Get videos like trailers for a specific title. |

## Request and Response Format  

**Request Example:**  
