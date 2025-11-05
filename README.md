# 🎬 Netflix Clone (Angular)

A responsive and feature-rich **Netflix Clone** built with **Angular 15**, designed to deliver a seamless movie browsing and viewing experience. It integrates with **The Movie Database (TMDB) API** to fetch real-time movie data, including trending titles, genres, and detailed descriptions.

---

## 🚀 Features

* 🎥 **Dynamic Movie Listings**: Browse trending, action, adventure, animation, comedy, documentary, sci-fi, and thriller movies.
* 🏠 **Home Page Carousel**: Display featured movies in an auto-sliding banner.
* 🔍 **Search Functionality**: Instantly find movies by title using the search page.
* 🧩 **Movie Details Page**: View complete details for a selected movie, including overview, ratings, and backdrop.
* 🌗 **Responsive Design**: Fully responsive layout built with Bootstrap 5 and Angular components.
* ⚡ **API Integration**: Fetches real-time data from TMDB API using Angular’s HttpClient.
* 🧠 **Clean Architecture**: Modular Angular structure following best practices for scalability.

---

## 🛠️ Tech Stack

| Category    | Technology                |
| ----------- | ------------------------- |
| Framework   | Angular 15                |
| Styling     | Bootstrap 5               |
| Language    | TypeScript                |
| API         | TMDB (The Movie Database) |
| HTTP Client | Angular HttpClientModule  |
| Forms       | Reactive Forms            |
| Build Tool  | Angular CLI               |

---

## 📂 Project Structure

```
othman-shbeir-netflix-clone-angular/
├── src/
│   ├── app/
│   │   ├── pages/
│   │   │   ├── home/            # Home page with carousels and movie categories
│   │   │   ├── movie-details/   # Movie details component
│   │   │   └── search/          # Search page for finding movies
│   │   └── service/             # API service layer
│   ├── assets/                  # Static assets
│   ├── index.html               # Main HTML entry
│   ├── main.ts                  # App bootstrap file
│   └── styles.css               # Global styles
└── angular.json                 # Angular project config
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/othman-shbeir/netflix-clone-angular.git
cd netflix-clone-angular
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Add Your TMDB API Key

* Open the movie API service file:

  ```bash
  src/app/service/movie-api-service.service.ts
  ```
* Replace the placeholder API key with your TMDB API key.

### 4. Run the Development Server

```bash
ng serve
```

Visit **[http://localhost:4200/](http://localhost:4200/)** to explore the app.

---

## 🧩 Available Scripts

| Command                        | Description                      |
| ------------------------------ | -------------------------------- |
| `ng serve`                     | Run the development server       |
| `ng build`                     | Build the project for production |
| `ng test`                      | Execute unit tests with Karma    |
| `ng generate component <name>` | Generate a new component         |

---

## 🧪 Testing

Run unit tests using:

```bash
ng test
```

Tests are powered by **Karma** and **Jasmine**.

---

## 📱 Responsive UI Preview

The layout is optimized for **desktop, tablet, and mobile devices**, ensuring a Netflix-like viewing experience across all screens.

---

## 🧠 Future Enhancements

* 🔐 User authentication and profile management.
* ❤️ Favorite movies and watchlist feature.
* 🌍 Multi-language support.
* 🎞️ Video streaming simulation with trailers.

---

## 👨‍💻 Author

**Othman Shbeir**
📧 [Email](mailto:uthmanshbeir@gmail.com)
🌐 [Portfolio](https://othman-shbeir.github.io)
🔗 [LinkedIn](https://www.linkedin.com/in/othmanshbeir)

---

## 📝 License

This project is licensed under the **MIT License** — feel free to use and modify it for learning or development purposes.
