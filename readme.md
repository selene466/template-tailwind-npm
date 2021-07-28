# Template Tailwind npm

### Description

This is my [Tailwindcss](https://tailwindcss.com/) template.  
Treesake is enabled. (purge)  
JIT is enabled.

### Installation

Clone this repo, enter repo directory, then run:

```sh
npm install
```

### Usage

Edit "src/tailwind.css", you can create it, you can also edit "package.json".

Run development server:

```
npm run dev
```

Will run tailwind-cli in watch mode & auto refresh web server if CSS files is
updated, thanks to browser-sync.  
Web browser, access [http://localhost:3000/](http://localhost:3000/).

Compiling CSS with PostCSS:

```
npm run buildcss
```

Compiled css will placed to "dist" directory.
