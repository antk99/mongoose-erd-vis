# Mongoose ERD Visualizer

This is a command-line tool designed to generate Entity-Relationship Diagrams (ERD) from Mongoose models in your Node.js applications. It helps visualize the relationships between the database schemas defined in your MongoDB using Mongoose.

## Features

- Supports various output formats including SVG, DOT, JSON, and more.
- Configurable options for ignoring files, setting colors, and specifying output paths.
- Easy-to-use command line interface.
- Free and open source.

## Installation

Just clone this repository.

## Usage

Once installed, you can run it from the command line with several options to customize the output.

## Command Line Options

```
-V, --version               Output the version number of MongoViz
-p, --path <path>           Set the path to the directory containing your Mongoose models
-o, --output <path>         Set the path and filename for the output ERD
-i, --ignore-index          Ignore any files named 'index.js'
-f, --format [format]       Specify the output format (svg, dot, xdot, plain, plain-ext, ps, ps2, json, json0)
-c, --color <color>         Specify the background color for collections in the diagram
-h, --help                  Display help for command
```

## Example

Make sure your terminal's working directory is the root folder of the cloned repository.

```bash
node bin/main.js -p ./path_to_models_folder/ -f svg -o ./erd.svg
```

## License

Mongoose ERD Visualizer is released under the MIT License. See the LICENSE file for more details.

## Acknowledgements

Thanks to <https://github.com/jodevsa/mongoose-erd-generator> for the inspiration behind this project.
