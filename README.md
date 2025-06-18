# odin-recipes

## Objective
Apply concepts of HTML and Git to build a basic webpage that links to other recipes.

## Concepts Covered

### HTML
- Basic page structure with boilerplate HTML.
- Headings using `<h1>` through `<h3>`.
- Paragraphs using `<p>`.
- Lists:
  - Unordered lists with `<ul>` and `<li>`.
  - Ordered lists with `<ol>` and `<li>`.
- Images using `<img src="" alt="">`.
- Hyperlinks with `<a href="">`.

### Git
- Initializing and cloning repositories with `git clone`.
- Tracking changes using `git add` and `git commit`.
- Pushing changes to GitHub with `git push origin main`.
- Using clear, descriptive commit messages.
- Structuring a project using directories (e.g., `/recipes`).

### GitHub
- Creating a public repository.
- Cloning repositories via SSH.
- Pushing local changes to GitHub.
- Publishing static web pages using GitHub Pages:
  - Navigating to repository settings.
  - Enabling Pages for the `main` branch.
  - Hosting at `https://<username>.github.io/odin-recipes/`.

## Project Structure

**odin-recipes/**

├── index.html # Main page linking to all recipes

└── **recipes/**

├── lasagna.html # Example recipe page
    
├── pancake.html # Additional recipe
    
└── pizza.html # Additional recipe

## Notes
- Each recipe page contains:
  - A title (`<h1>`).
  - An image of the dish.
  - A description section.
  - An ingredients list (`<ul>`).
  - A steps list (`<ol>`).
  - A link back to the index/home page.

- The index page contains:
  - A heading (`<h1>Odin Recipes</h1>`).
  - A list of links to individual recipes (`<ul><li><a></a></li></ul>`).

## License
MIT License - free for educational and personal use.
