
# Obsidian Markdown Guide


## Project Setup

To get started with this project, follow these steps:

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/gabe-grant/dnd
   ```

2. **Navigate to the Project Directory:**
   ```sh
   cd [your-project-directory]
   ```

3. **Open in VS Code:**
   - Open Visual Studio Code.
   - Use `File > Open Folder` to open the cloned project directory.

4. **Run the Project:**
   - If your project requires running, ensure you have the necessary extensions installed. For example, for JavaScript:
     - Open the integrated terminal in VS Code (`Ctrl + ` ` on Windows/Linux or `` Cmd + ` ` on macOS).
     - Run `npm install` if using Node.js to install dependencies.
     - Then run `npm start` or whatever command is appropriate for your project.

## Markdown in Obsidian

Obsidian uses Markdown for note-taking, which allows you to format your text easily. Here are some common Markdown features you can use within Obsidian:

### Basic Text Formatting

- **Bold:** Surround text with double asterisks `**bold text**`.
- *Italic:* Use single asterisks `*italic text*`.
- ~~Strikethrough~~: Use double tilde `~~strikethrough~~`.

### Headers

Headers are created using hash symbols (`#`). The number of hashes determines the heading level:

- `# H1`
- `## H2`
- `### H3`
- `#### H4`
- `##### H5`
- `###### H6`

### Lists

- **Unordered Lists:** Use `-`, `+`, or `*` at the beginning of lines:
  - `- Item 1`
  - `- Item 2`

- **Ordered Lists:** Use numbers:
  1. `1. First item`
  2. `2. Second item`

### Links and Images

- **Links:** `[Link text](URL-or-path)`
- **Images:** `![Alt text](URL-or-path)`

### Code Blocks

- **Inline Code:** Use single backticks for inline code: ` `code` `.
- **Code Blocks:** Use triple backticks for blocks:
  ``` 
  ```
  You can specify the language after the opening backticks for syntax highlighting, e.g., ```javascript.

### Special Obsidian Features

- **Internal Links:** Link to other notes within your vault using `[[Note Name]]`.
- **Embedding:** Embed notes, images, or other media directly in your notes with `![[Note Name]]` or `![[image.png]]`.
- **Callouts:** Use for highlights or special notes:
  ```
  > [!note]  
  > Here's some important information.
  ```

- **Checklists:** Create interactive checklists:
  - `[ ] Unchecked`
  - `[x] Checked`

### Tips for Using Markdown in Obsidian

- Use the live preview mode to see your formatting in real-time as you type.
- Obsidian supports many plugins that extend Markdown functionality, like tables or Mermaid diagrams for flowcharts.
- Remember, Obsidian treats each `.md` file as a note, which can be linked to create a knowledge graph.

This guide should help you get started with using Markdown in Obsidian while also setting up your project in VS Code. Enjoy organizing your thoughts and knowledge with these tools!
```