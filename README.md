# 🎬 React Movies Web App  
This project is a movie search and trending list app built with React and Vite.  
It basically follows the YouTube tutorial by [JavaScript Mastery](https://www.youtube.com/watch?v=dCLhUialKPQ&t=308s).

![Image](https://github.com/user-attachments/assets/51e6392d-34c3-415e-965d-3b1018c3280f)

## 🚀 Features  
✅ Fetches and displays default movie data from [The Movie DB](https://www.themoviedb.org/) when the app is mounted.  
✅ Allows users to search for movies dynamically.  
✅ Stores the searched movies in [Appwrite](https://appwrite.io/) and displays trending movies based on the order of search frequency.  
✅ Uses `useDebounce` to optimize API requests and prevent excessive calls.  

## 🛠️ Technologies Used  
- **React 19** (with Vite)  
- **Appwrite** (for backend storage)  
- **The Movie DB API** (for fetching movie data)  
- **useDebounce Hook** (for efficient search)

## 📽️ Demo Video<br>
![Image](https://github.com/user-attachments/assets/5f7e919d-06dd-4183-a02a-ef25d3a4e677)

## Getting Started  
### Prerequisites  
- Install **[Node.js](https://nodejs.org/)**  
- Install **[Vite](https://vitejs.dev/)** (optional, since it's included in dependencies)  

### Installation & Running the App  
1. Clone the repository:  
   ```sh
   git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME.git
   cd YOUR_REPOSITORY_NAME
2. Install dependencies:
   ```sh
   npm install
3. Run the app locally:
   ```sh
   npm run dev
4. Open the app in your browser:
