#  Mini Movie Explorer

A responsive React + Vite app for searching movies and managing a personal watchlist using the OMDb API.

Built with modular components, Tailwind CSS for styling, and localStorage for persistent state.



##  Demo






##  Tech Stack

- ⚛️ React 18
- ⚡ Vite
- 💨 Tailwind CSS
- 🧩 Modular Component Structure
- 🧠 React Hooks (`useState`, `useEffect`)
- 💾 localStorage
- 🏷️ PropTypes (for type safety)

---

## 📁 Project Structure

src/
├── Components/
│ ├── Box/
│ ├── ErrorMessage/
│ ├── Loader/
│ ├── Logo/
│ ├── Main/
│ ├── Movie/
│ ├── Movielist/
│ ├── Navbar/
│ ├── NumResult/
│ ├── Search/
│ ├── SelectedMovie/
│ ├── StarRating/
│ ├── WatchedList/
│ └── WatchedSummary/
├── assets/
│ └── react.svg
├── App.jsx
├── App.css
├── index.css
├── index.js
├── main.jsx
├── UseLocalStorageState.js


Each folder inside `Components/` holds a modular functional component with scoped logic and styles.



##  Features

###  Search
- Uses [OMDb API](http://www.omdbapi.com) to search movies by title
- Debounced input (500ms)
- Fetches up to 10 results with poster, title, and year

###  Watchlist
- Add movies via `+ add to list` button
- Prevents duplicates
- Watchlist stored in `localStorage` for persistence

###  Responsive Layout
- Mobile-first using Tailwind CSS
- Grid/column layout for screens `≥768px`

###  Clean Architecture
- Split components (Search, MovieList, SelectedMovie, etc.)
- Custom hook: `UseLocalStorageState.js`
- `PropTypes` used for runtime prop type-checking

---

##  Getting Started
npm run dev


