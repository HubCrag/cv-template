## Hubcrag CV Template

### [Watch it on youtube](https://youtu.be/4dQ5U2x8JkY)

### Setup demo project

`npm install` or `yarn install`

### Start demo project

`gulp` or `gulp serve` deploy app and start browsersync server + watchers

## File structure
```bash
├── /build/                     # Temporary served files
└── /src/                       # The source code of the application
    ├── /js/                    # JavaScript source
        └── /vendor/            # Js libraries
    ├── /partials/              # Html templates
        └── /_includes/         # Html partials
        └── /part/              # Html parts
    ├── /scss/                  # SCSS styles
        └── /components/        # Scss components
        └── /vendor/            # Css or scss libraries
    ├── /static/                # Static files (fonts, images, videos, etc..)
