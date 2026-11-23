# Fashion Zone POS: online demo

Live demo: https://darshanchopda-ux.github.io/fashion-zone-pos-demo/

This is a billing and inventory app for a clothing shop. The real app is a Windows desktop app (Tauri, React and Rust, with SQLite) that works offline. For this demo, the same Rust backend is compiled to WebAssembly and runs in your browser, with a made-up shop and a database held in memory. Nothing you do here is saved or sent anywhere, and the demo resets when you reload the page.

New: on **Add purchase**, "Read a bill photo" uses AI (Google Gemini, called through n8n) to fill in the rows from a distributor's bill. Try it with the built-in sample bill. Nothing saves until you check the rows.

- Owner PIN: 4827
- Cashier PIN: 5938

This repo only holds the built demo files. The source code is private.
