# **Spotify Clone ( Full-Stack Web App )**

This is a full-stack **Spotify Clone** built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**. It provides users with an immersive music streaming experience featuring **song playback**, **custom playlists**, and an **admin panel** for managing music content.

---

## **Features & Highlights:**

### 1. **Admin Panel**  
  - Add, edit, or remove **songs**. 
   - Manage song metadata (title, artist, album, artwork, etc.).  
   - Fully protected and accessible only to admin users.

### 2. **User Playlists**  
   - Each user can add or remove their preferred songs in the playlist.
   - Add/remove songs to/from playlists easily.

### 3. **User Authentication**  
   - Secure login & signup using JWT.  
   - Protected routes for authenticated users and admin controls.

### 4. **Responsive UI**  
   - Mobile-first design using **TailwindCSS**.  
   - Works smoothly across devices of all screen sizes.

---

## **Pages**

### 1. **Home Page**  
- Displays Top Trending Songs.  
- Playback controls and quick-access playlists.  

### 2. **Admin Dashboard**  
- Add/remove/update songs and playlists.  
- Manage content metadata.

### 3. **Playlist Page**  
- Shows user-created or admin-curated playlists.  
- Songs can be added to and removed from playlists.

### 4. **Search Page**  
- Search results based on input query (song name, artist, album).

### 5. **Song Detail Modal/Page**  
- View full details and play song in full screen or popup player.

---

**Tech Stack**

![My Skills](https://skillicons.dev/icons?i=mongodb,express,react,nodejs,js,html,css,tailwind)

- **MongoDB**: Stores songs, users, playlists, and metadata.  
- **Express.js**: Backend API routing and middleware.  
- **React.js**: Frontend UI using functional components.  
- **Node.js**: Backend server runtime.  
- **JWT**: Authentication & authorization.  
- **Axios**: HTTP requests for data fetching.  
- **Tailwind CSS**: Fast and responsive UI styling.  
- **React Router**: Client-side navigation.  
- **Bcrypt.js**: Password hashing.  
- **React Hot Toast**: Pop-up notifications.  
- **Lucide React**: Modern icons for controls and UI.  

---

**Screenshots**

**Desktop View**

> *(Add screenshots of Admin Panel, Home Page, Music Player, Playlist Page here)*  
`<img src="URL" alt="Spotify Clone Desktop View" width="320" />`

---

**Mobile View**

> *(Add screenshots of mobile UI components)*  
`<img src="URL" alt="Spotify Clone Mobile View" width="220" height="500" />`

---

**Installation & Setup**

Clone the repo and install dependencies for both **client** and **server**:

```bash
# Frontend
cd client
npm install

# Backend
cd server
npm install
```

**Environment Variables (Backend):**  
Create a `.env` file in the `server/` directory and include:

```env
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

**Run the App:**

```bash
# Start backend server
cd server
npm run dev

# Start frontend
cd client
npm start
```

---

**Contributing**

Feel free to contribute to improve this clone:

1. Fork the repo  
2. Create your branch (`git checkout -b feature/YourFeature`)  
3. Commit your changes  
4. Push to the branch  
5. Open a pull request

---

**License**

MIT License © 2025 [Your Name]

---  

Let me know if you need further adjustments!
