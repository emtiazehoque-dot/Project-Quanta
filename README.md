# Quanta Notes
> A next-generation note-taking app powered by a custom Markdown language.



## About this project 
This project is an `open-source` effort to create a simple yet powerful note-taking app. We aim to build an application that has more functions than a typical note app by implementing a `new type of markdown`, which retains the simplicity of classic Markdown, and we are developing it in-house. This markdown will be backwards compatible, so the present files will work in the new renderer and the new files will work in older renderers. 

Additional features we are planning to add is the ability to **generate complex HTML files** will embedded CSS (inline and style taged) and JS. Basically replacing *(mostly)* frontend-hard-work with markdown simplicity. Keep an eye on the markdown project - `Ethium` - for updates. 

## Key Features *(Planned and Ongoing)*

- **Enhanced Markdown Support:** Integrating Ethium, a custom Markdown flavor that supports styling and layout control.

- **HTML, CSS & JS Export:** Generate complete HTML pages (with inline and `<style>` CSS and embedded JS) directly from notes.

- **Cross-Platform Desktop App:** Built with Electron for Windows, macOS, and Linux, designed to be fully offline.

- **Backwards Compatibility:** Old Markdown stays readable. Unsupported features degrade gracefully.

- **Modular Design:** Easily extensible architecture to add plugins, syntax extensions, and tools in future updates.



## Q&A

- About Backwards Compatibility

It means your files won’t break. Opening an Ethium file in a normal Markdown renderer will still show readable content and vice versa. If any feature doesn't work, then it will be marked in a way that it won't get in the main context. 

- About Generating Complex HTML file

This app will be able to generate complex HTML files that can be used as dynamic web page *(to an extent)*. We want to put as much customizability as possible. This feature is mostly from the markdown we are developing, so take a look at `Ethium Markdown project` for more details. 

- About the platform

Initially, the app will run on Windows, macOS, and Linux, with offline-first support. If we make it out alive and get some positive feedback, we might think about other platforms as well. 

### Contributing

We welcome contributors who appreciate clean syntax, modular code, and chaotic creativity.
If you want to help improve Ethium Markdown or this app, open an issue, suggest ideas, or submit pull requests. (Ethium will go public soon)


### License

MIT License – free to use, modify, and redistribute.
