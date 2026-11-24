# ARLimited — Explainable MovieLens AI Streaming Platform

A complete, zero-backend **Personalized Movie Recommendation System** built with HTML5, Tailwind CSS, and Vanilla JavaScript using the **MovieLens** benchmark dataset structure.

## Features
- **Home Page:** Spotlight hero banner and live dynamic carousels including *Top AI Picks For You* that adapt as you rate movies or update playlists.
- **Discover & AI Recommender:** Switch between **Hybrid AI**, **Content-Based Filtering (TF-IDF + Cosine Similarity)**, and **Item-Based Collaborative Filtering** with human-readable explanations for every recommendation.
- **My Playlists:** Manage multiple custom playlists (*Watchlist*, *Weekend Binge*, *All-Time Favorites*, or create your own) and generate AI recommendations tailored to an entire playlist.
- **User Profile & Cinema Taste DNA:** Edit your profile, track star ratings, and visualize real-time genre affinity telemetry persisted in `localStorage`.

## How to Host on GitHub Pages
1. Create a new public repository on GitHub (e.g., `ARLimited-Movie-Recommender`).
2. Upload `index.html` and `README.md` to the root of the repository.
3. Go to **Settings → Pages → Build and deployment**.
4. Under **Branch**, select `main` and `/ (root)`, then click **Save**.
5. Your live website link (`https://<your-username>.github.io/<repo-name>/`) will be ready within 1–2 minutes.
