# WebRTC Basic

A simple WebRTC-based video chat application that enables peer-to-peer communication between users.

## Features
- Peer-to-peer video calling using WebRTC
- Simple UI with minimal setup
- Screen Sharing functionality
- Join room functionality

## Technologies Used
- WebRTC
- JavaScript
- HTML
- CSS

## How to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/adityasgit25/WebRTC-basic.git
   ```
2. Navigate to the project directory:
   ```sh
   cd WebRTC-basic
   ```
3. Install dependencies (if applicable):
   ```sh
   npm install
   ```
4. Start the server:
  First go to the backend folder.
   ```sh
    tsc -b
    node dist/index.js
   ```
5. Start the client:
  first go to the frontend folder:
   ```sh
    npm run dev
   ```
6. Open a web browser and go to:
   ```
   http://localhost:5173/sender
   http://localhost:5173/receiver
   ```

## How It Works
- The application initializes a WebRTC connection.
- Users can start a video call by connecting with another peer.
- Media streams (audio/video) are exchanged directly between peers.

## Requirements
- A modern web browser (Chrome, Firefox, Edge, etc.)
- A webcam and microphone (optional but recommended)

## Notes
- This is a basic implementation; for real-world applications, a signaling server is required to establish the connection between peers.
- The app may not work if both users are behind restrictive NATs/firewalls.

## Contributing
Feel free to fork this repository, make changes, and submit a pull request.

## License
This project is licensed under the MIT License.

---

### Author
[Aditya Maheshwari](https://github.com/adityasgit25)
