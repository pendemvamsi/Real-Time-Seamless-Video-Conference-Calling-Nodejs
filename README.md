# Conference Call Implementation with WebRTC, Socket.io, and Node.js

## Description:
This project provides a simple yet robust implementation of a conference call system using WebRTC for real-time communication, Socket.io for handling WebSocket connections, and Node.js for server-side logic. With features like multi-participants support, video/audio stream toggling, screen sharing, text chat, and more, it offers a comprehensive solution for small-scale virtual meetings.

## Key Features:

1. **Multi-participants:** Connect up to four devices simultaneously for seamless conferencing.
2. **Video and Audio Control:** Toggle video and audio streams, allowing users to mute/unmute as needed.
3. **Screen Sharing:** Share your screen to enhance collaboration and presentations.
4. **Text Chat:** Communicate via text messages within the conference interface.
5. **Individual Mute:** Mute/unmute individual participants to manage audio output effectively.
6. **Stream Expansion:** Expand participants' streams for better visibility.
7. **Screen and Video Recording:** Record screen and video for future reference or archiving.

## Screenshots:

1. **Conference Interface:**
   ![Conference Interface](conference_interface.png)
   *Explanation: The main interface showing multiple participants with options for video/audio control and text chat.*

2. **Screen Sharing:**
   ![Screen Sharing](screen_sharing.png)
   *Explanation: A participant sharing their screen with others during the conference.*

3. **Text Chat:**
   ![Text Chat](text_chat.png)
   *Explanation: Text chat functionality allowing participants to communicate alongside video/audio conferencing.*

4. **Recording Options:**
   ![Recording Options](recording_options.png)
   *Explanation: Options for screen and video recording for archival purposes.*

## GitHub Installation:
You can install and deploy this project from its GitHub repository:

Repository Link: [Conference Call WebRTC Node.js](https://github.com/example/conference-call-webrtc-node)

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run `npm ci` to install dependencies.
4. Customize configurations as needed (e.g., ICE server settings).
5. Start the server using `node app.js` or `npm start`.



## Note:
For ICE server configuration, you may need to create a free Xirsys account or use alternative ICE servers and update the settings in `src/assets/js/helpers.js`.

## Alternative:
If you prefer using PHP WebSocket (Ratchet) instead of Socket.io and Node.js, you can explore the PHP version [here](https://github.com/example/php-websocket-conference).
