## When AI goes off script - Tales from the docs pipelines

This repository contains the source code for the presentation *When AI goes off script - Tales from the docs pipelines* by Marco Spinello.

The presentation explores the use of AI in documentation pipelines, highlighting the benefits and drawbacks through real-world examples.

### Get started

#### Prerequisites

To build and view the presentation, you need to have Node.js and npm installed.

#### Steps

1. **Clone** the repository:

    ```bash
    git clone https://github.com/your-username/talk-ai-api-docs.git
    cd talk-ai-api-docs
    ```

2. **Install** the dependencies:

    ```bash
    npm install
    ```

3. **Serve** the presentation:

    ```bash
    npm run marp:serve
    ```

    This starts a local server at `http://localhost:9999` where you can view the presentation.

    The local server watches for changes to the Markdown files and reloads the presentation automatically.

### Build

You can build the presentation in HTML, PDF, and PPTX formats:

- **HTML:**

    ```bash
    npm run marp:html
    ```

- **PDF:**

    ```bash
    npm run marp:pdf
    ```

- **PPTX:**

    ```bash
    npm run marp:pptx
    ```

The output files are saved to the `output` directory.

## Author

Marco Spinello

## License

This project is licensed under the terms of the `LICENSE` file.
