# Age of Empires II Maps Project

A web tool for **randomly selecting maps and civilizations** for Age of Empires II.  
Tracks the last 5 picks for maps and civs and ensures **no repeats until all civs are picked**. Persistent across sessions using **Supabase** as the backend.

## Project URL
https://abhishekp90-github-io.vercel.app/

## Project Structure
- `index.html`: Main webpage for the project.
- `script.js`: Javascripts used in page.
- `style.css`: Page styles.
- `images/`: Contains images used in the project (e.g., `Aoe2.jpg`).

## Usage
- Open `index.html` in your browser to view the site. Images are in the `images/` folder.
- Database is hosted on supabase.com which contains maps, civs, history, etc

## Features
- **Random Map Picker**
  - Picks a map from the database.
  - Stores the **last 5 picked maps** in the database.
  - Prevents repeating maps until all available maps are picked.

- **Random Civ Picker**
  - Picks civilizations no DLC  and with DLC civs.
  - Tracks **remaining civs** in the database to avoid repeats.
  - Stores and displays **last 5 civs picked** for each player.

- **Host Button**
  - Randomly selects either **A** or **B**.

- **Reset Button**
  - Clears map history and resets remaining civ pools.
  - Resets civs for both players.

- **Mobile-friendly**
  - Fully responsive layout.
  - Works on desktops and mobile devices.

## Contributing
Feel free to add new maps to `maps.txt` or update the site as needed.

## License
This project is open source and free to use.
