# Interactive Economic Flowchart and Simulation

This project visualizes the economic interactions and liquidity flows of a hybrid cryptocurrency-fiat ecosystem using **D3.js** and provides an economic simulation for reserves and revenue tracking.

## Features
1. **Interactive Flowchart**:
   - Visualize transactions and asset flows.
   - Nodes and links represent parties, blockchains, and financial transactions.
   - Dynamic layout with draggable nodes and scalable links.

2. **Economic Simulation**:
   - Simulates liquidity reserves, revenue streams, and asset flows.
   - Tracks GRU distribution across chains and regions.

3. **Real-Time Updates**:
   - Supports JSON data for dynamic updates to nodes and links.
   - Configurable via external files or APIs.

---

## File Structure
### Core Files
- **`index.html`**: The main HTML file with embedded D3.js for the flowchart.
- **`js/simulation.js`**: Handles the economic simulation logic.
- **`data/nodes.json`**: Defines the entities in the flowchart (e.g., Saudi Arabia, GRU Reserve).
- **`data/links.json`**: Defines the relationships and transaction values between entities.

### Optional Files
- **`css/styles.css`**: Customizable styles for the flowchart and simulation UI.
- **`scripts/server.py`**: A simple Python server for local hosting.

---

## Installation
### Prerequisites
- **Node.js** (optional for serving the project)
- **Python 3.x** (if using the included server script)
- Modern web browser (Chrome, Firefox, etc.)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name/interactive-flowchart.git
   cd interactive-flowchart
