# GameWisp-Emote-Examples
Examples of how to use GameWisp's various emote APIs in your application

## GameWisp Emote WebSocket API
The Emotes WebSocket API is real-time API that is meant to be interacted with solely using WebSockets. Clients connect to the API and listen to specific events of interest and receive data from the API in real-time. **Unlike a conventional REST API, there is no need to repeatedly poll or request on specific endpoints.** This API is ideal for bots and other services that require immediate and on-going access to GameWisp data.

Currently, the **Emotes WebSocket API is read only**. Connected clients can receive data in real-time, but can perform no operation which alters the state of any data stored by GameWisp.

**This API is fully documented [here](https://gamewisp.readme.io/docs/getting-started).**

Examples:
  * [Socket-Client-App](https://github.com/GameWisp/GameWisp-Emote-Examples/tree/master/examples/Socket-Client-App/index.html) - A single page application that interacts with the GameWisp Emote WebSocket API directly in the browser.

## Questions, Comments, Etc.

These APIs are an actively developed work in progress, and are considered beta software. If you have any recommendations, suggestions, or issues, feel free to file a GitHub issue on this repository, or email us at help [at] gamewisp [dot] com.

If you would like to include a working example of your own to this project, please submit a pull request. We're particularly interested in simple examples that leverage different programming languages outside of JavaScript.