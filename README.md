# Home
The home repository for Otako. Find everything related to Otako here, it's documentation, contribution, and sources to all of Otako's repositories.

If you'd like to chat with us, we have a Discord server for development purposes, which can be found by clicking [here.](https://discord.gg/8g2D7Dv)

[![dev chat](https://discordapp.com/api/guilds/380173469322575874/widget.png?style=banner2)](https://discord.gg/8g2D7Dv)
 
# ! Initial Release !
As of 11/14/2017 (MM/DD/YYY) we have gone open source and we're still merging our new changes. All of our repos will be filled with information ASAP and this repo will be updated and documented. For now, just chill in the cool lane. :sunglasses: 

Anyhow, please do note we aren't accepting contributions as most of our code is currently privately hosted, very badly written, undergoing rewrites and major changes, and lastly, is not ready for open source. Before we can go open source, we'll need to finish up some things and merge our new code to here.

Thanks for being curious about Otako and thanks for helping us build this amazing application!

# Repositories
Kibii has created several repositories to seperate and organize Otako's code. Here's a list of all the repositories and what's inside them:
* [otako](https://github.com/KibiiTV/otako/) - The home repo for Otako. This contains a homepage for where everyone needs to go to find any of the other repositores, their purpose, documentation, and central hub for everything Otako.
* [otako.moe](https://github.com/KibiiTV/otako.moe/) - The statically served frontend and UI for Otako. This is a combination of HTML, CSS, and JavaScript to create the beautiful frontend of Otako!
* [otakoapp](https://github.com/KibiiTV/otakoapp/) - The RESTful API backend for Otako. This is where everything happens, from account registration, to message handling, to database handling, this repository contains the code to do everything for Otako. It serves almost everything needed to bring Otako up and running.
* [otakoclient](https://github.com/KibiiTV/otakoclient/) - This repository is the Electron client for Otako. This is the desktop app supported on multiple platforms and is designed to load the statically served frontend. This repository isn't something you can contribute to. If you'd like to build Otako's frontend, you'd like to check out the [otako.moe](https://github.com/KibiiTV/otako.moe/) repo.
* [otako.ws](https://github.com/KibiiTV/otako.ws/) - This is the WebSocket presence Gateway that recieves and dispatches realtime events to Otako from the REST backend. This contains all the code that the RESTful backend uses to comminicate to the WebSocket, and the code that communicates events in real-time from the WebSocket to the client, while keeping everyone safe, secure, in a friendly environment.
* [otako.docs](https://github.com/KibiiTV/otako.docs/) - This repository contains a to-do list, project list, Wiki, and planned features for what's to come next in Otako. It also contains the core documentation to all of the API, internal and external. This repository contains the **specification** as to how Otako is designed, works, and flows all in once piece. Have a read through this if you want to know what you want to develop, or to understand how Otako is designed.
* [otako.net](https://github.com/KibiiTV/otako.net/) - This is the .NET/C# wrapper for Otako's API. This allows programmers to communicate with our API, so they can create amazing applications and bots wrapped around Otako.
* [otako.js](https://github.com/KibiiTV/otako.js/) - This is the Node/JavaScript wrapper for Otako's API. This allows node.js and web js programmers to communicate with our API, so they can create amazing applications and bots wrapped around Otako.
* [otakoapp-website](https://github.com/KibiiTV/otakoapp-website/) - This is the landing page for Otako's website (found at http://otakoapp.com) until development has advanced far enough where we can host a basic version of Otako. Until then, this landing page serves Otako and displays basic information.

# Domains
As of now, Kibii has acquired these domains for Otako:


* **otako.moe**
* **otakoapp.com**
* **otakoapp.org**
* **otakoapp.net**
* **otaa.co**


The domains otakoapp.net and otakoapp.org will redirect to otakoapp.com which will be the core landing page for Otako. 
We're currently still discussing where to serve our API from, WebSocket, and frontend from.


So far we're thinking about serving our API from `api.otakoapp.com`, serving our Invite URI from `otaa.co`, our UI from `chat.otako.moe` and our Presence server at `ws.otako.moe`.

If you are sent a link to a different domain, it is not affiliated with Otako and should not be clicked on. (Exceptions apply to Kibii's domains).
