#  CookGPT |  Smart Recipe Finder

A simple recipe search app using the **EDAMAM API**.  



---

##  Features  
 
- Learn React + TailwindCSS + EDAMAM API
- Build a Responsive Design
- Docker support for easy development and deployment

---
## Tech Stack
- React.js
- TailwindCSS
- Zustand (for global state management)
- EDAMAM API

---
##  Run with Docker

### 1️.Build and Run

Make sure Docker is installed, then run:

```bash
docker-compose up --build
```
The app will be available at:

```arduino
http://localhost:3000
```

### 2️.Environment Variables

Create a `.env` file in the root directory (same as `Dockerfile`) and add:

```env
VITE_APP_ID=your_edamam_app_id
VITE_APP_KEY=your_edamam_app_key
```
You can use .env.local for local development, but make sure it’s copied into the image when Dockerizing.

### 3️.Docker Files Included

- `Dockerfile` – builds the app container  
- `docker-compose.yml` – runs the container with necessary settings  
- `.dockerignore` – avoids copying unnecessary files to the image

---

##  Run Locally  

### 1️.Setup `.env` File  
Create a `.env` file in the root directory and add:  

```env
VITE_APP_ID = your_edamam_app_id
VITE_APP_KEY = your_edamam_app_key
```

### 2️.Install Dependencies  
Run the following command to install all required packages:  

```sh
npm install
```

If using **Yarn**, run:  

```sh
yarn install
```

### 3️.Start the App  
To start the development server, run:  

```sh
npm run dev
```

or with **Yarn**:  

```sh
yarn dev
```

---

##  UI Design  
The app is built with **TailwindCSS** and **DaisyUI** for a modern and responsive look.  

---

##  Deployment  
Deploy the app for free using:  
- **Vercel**  
- **Netlify**  

---

##  Contribute  
Feel free to submit issues or feature requests! 



---

Happy coding! 
