# CAB402-Programming-Paradigms
Dr Wayne Kelly | Notes for CAB402 at the Queensland University of Technology

## Preface
Everything written here is based off the QUT course content. However, there are at times parts of text that are taken from the QUT slides and most of the examples are directly from the course slides (these are referenced when done). This content is designed only for those currently studying an IT degree at QUT, do not share these resources with anyone outside of this community. 

If any member of the QUT staff or a representative of such finds any issue with these guides please contact me at jeynesbrook@gmail.com and I will take these down without an argument. The last thing I want to do is cause any issues or damages to the QUT name or QUT resources. I am simply just trying to help students out with presenting the content in an easy to digest manor.

## How to use this guide
1. Install [NPM](https://docs.npmjs.com/cli/v7/configuring-npm/install)
2. Install [serve](https://www.npmjs.com/package/serve)
3. Navigate to the `book` directory and serve the files
```bash
cd <project>/book
serve
```
4. Open up the corresponding URL in your browser e.g. http://localhost:3000 

## Building locally
1. Install [Cargo](https://doc.rust-lang.org/cargo/getting-started/installation.html) 
2. Install [mdbook](https://rust-lang.github.io/mdBook/guide/installation.html)
3. Install [mdbook-quiz](https://github.com/cognitive-engineering-lab/mdbook-quiz)
4. Serve the book
    - Via NPM
        1. Build the book
        ```bash
        mdbook build
        ```
        2. Serve the book
        ```bash
        cd <project>/book
        serve
        ```
    - Via mdBook
        1. Serve the book
        ```bash
        mdbook serve --open
        ```

## Disclaimer
Although these documents may provide a decent learning experience on their own it is highly advised that you use these in-part with the lectures notes and videos provided to you by your lecturer. This is mainly due to the fact that overtime these guides may become outdated as the units themselves get updated.

It is also important to remember that these guides are written by students and as part should always be taken with a grain of salt, always read further into topics you don't understand and always do your own research on topics. These guides are designed to give you a brief description on each topic giving you a nice overview of the unit and a solid exam time revision document.

A note for programming units, when it comes to programming the best way to learn is not by reading theory but by practising in a practical way. Follow along with the guides but customize the exercises to your liking and make an attempt to utilise the language being learnt in home projects of your own.
