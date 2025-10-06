# 🎬 MoviesDatabase API

##  API Overview
MoviesDatabase is a comprehensive movie, series, and episode information service. It provides data on over **9 million titles** and **11 million cast and crew members**. You can access details such as:
- Biographies  
- Awards  
- YouTube trailer URLs  
- Other rich metadata  

Source: [RapidAPI](https://rapidapi.com)

---

##  Version
The API version isn’t explicitly stated in the available documentation.  
Please check the RapidAPI introduction panel or API response headers for version details.

---

## 🔗 Available Endpoints
While full endpoint documentation isn’t publicly visible, typical endpoints include:

- **Search Titles** — Find movies or shows by title or keywords  
- **Get Title Details** — Retrieve comprehensive information for a specific title (e.g., cast, synopsis, awards)  
- **Get Person Details** — Fetch biographies and filmography for actors or crew  
- **Get Trailer** — Obtain a YouTube trailer link for a specific title  

>  Refer to the RapidAPI playground panel for the exact list, parameter names, and URL paths.

---

##  Request and Response Format

###  Request
- Method: `GET`  
- Parameters: Query strings (e.g., `?query=Inception`)  
- Headers: Include necessary authentication and content-type headers

###  Response
Typically returned in JSON format:
```json
{
  "title": "...",
  "year": "...",
  "actors": [ ... ],
  "awards": "...",
  "trailer_url": "..."
}
