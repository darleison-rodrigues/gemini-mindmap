# Gemini Mindmap Extension

A Gemini CLI extension that automatically generates beautiful Mermaid mindmaps from your Markdown documentation.

## Features

- **Slash Command:** `/mindmap <file>` to generate a diagram on demand.
- **Smart Formatting:** Automatically maps headers to node shapes (Root `(( ))`, Branch `[ ]`, Leaf `text`).
- **Concise:** Enforces short node labels for readability.

## Installation

1.  Clone this repository:
    ```bash
    git clone https://github.com/darleisonfilho/gemini-mindmap.git
    cd gemini-mindmap
    ```

2.  Link the extension to your Gemini CLI:
    ```bash
    gemini extensions link .
    ```

3.  Restart your Gemini CLI session.

## Usage

In your Gemini CLI session:

```bash
/mindmap README.md
```

Gemini will read the file, analyze the structure, and save a `README.mindmap.mmd` file in the same directory.

## Requirements

-   Gemini CLI installed.
-   A mermaid-compatible viewer (like GitHub or a VS Code extension) to view the `.mmd` files.
