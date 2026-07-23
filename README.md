# TERRALUXwiki

Interactive Study Portal for **TERRALUXwiki** built using Hugo.

## Features
- **Year 2000 Retro UI**: A classic Windows 2000 / Web 1.0 inspired theme featuring Tahoma system fonts, 3D outset/inset bevel panels, and classic desktop grey aesthetics that are extremely easy on the eyes.
- **Collapsible Directory Tree**: Clean, empty homepage displaying categories as a collapsible folder tree. Clicking folders expands/collapses the topics list dynamically via lightweight JS.
- **Pagefind Static Search**: High-performance, client-side search indexing powered by Pagefind. Designed to scale seamlessly to 100,000+ pages with minimal memory footprint and instant search feedback.
- **Reading Mode & Navigation**: Clean documentation-style page reading layouts, sidebar indices for quick jumps between chapters, and dynamic title resolution using base filenames for clean navigation.
- **Visual Flowcharts**: Integrated interactive Mermaid.js diagram notes to visualize conceptual connections in Climatology and Economic Geography.

## How to Run and Test Locally

### 1. Build and Run Hugo Server
To preview the website structures on your local machine:
1. Ensure you have [Hugo](https://gohugo.io/) installed.
2. Run the Hugo development server:
   ```bash
   hugo server
   ```
3. Open your browser and navigate to `http://localhost:1313`.

### 2. Testing Pagefind Search Locally
Since Pagefind is a static search indexer that runs on the compiled HTML:
1. Generate the static site and index the pages:
   ```bash
   hugo
   npx pagefind --site public
   ```
2. Serve the generated `public/` folder using any static file server (e.g. `npx http-server public/`) to test the Pagefind search box locally.
