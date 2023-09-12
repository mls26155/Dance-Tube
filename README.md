# DanceTube - Your Ultimate Dance Video Platform

DanceTube is a web application that allows users to explore and share dance videos. It offers a seamless dance video experience, from watching captivating performances to uploading your dance creations.

![image](https://github.com/mls26155/Dance-Tube/assets/101059605/e4d12490-cc0a-4efb-b46f-d56949367cdd)

## Features

- **List Videos:** Discover a wide range of dance videos from various genres.
- **Watch a Video:** Enjoy high-quality video playback for an immersive viewing experience.
- **Sign In/Out:** Create an account or log in to access additional features.
- **Upload a Video:** Share your dance videos with the global dance community.
- **Watch Transcoded Video:** Experience smooth video playback with optimized transcoded content.

## Tech Stack

- TypeScript
- Next.js
- Express.js
- Docker
- FFmpeg
- Firebase Auth
- Firebase Functions
- Firebase Firestore
- Google Cloud Storage
- Google Cloud Pub/Sub
- Google Cloud Run

## Getting Started
![image](https://github.com/mls26155/Dance-Tube/assets/101059605/deb90a6c-4f69-45c6-9d7f-b134e9137b5c)
![image](https://github.com/mls26155/Dance-Tube/assets/101059605/aa44da53-d6be-46a3-8bec-8d38a8170b1f)

To get DanceTube up and running on your local machine, follow these steps:

1. Clone this repository.
2. Install project dependencies with `npm install` or `yarn install`.
3. Configure your Firebase project and set up the necessary credentials.
4. Run the application locally with `npm run dev` or `yarn dev`.

View a demo here: https://yt-web-client-pyceld7pfq-uc.a.run.app/

## Architecture

DanceTube's architecture is designed for scalability and performance. Key components include:

- **Cloud Storage:** Stores user-uploaded videos.
- **Pub/Sub:** Facilitates communication for video processing.
- **Cloud Run (Video Processing):** Efficient video transcoding and upload service.
- **Cloud Firestore:** Stores video metadata.
- **Cloud Run (Web Client):** Hosts the Next.js web app.
- **Firebase Functions:** Backend logic for fetching and serving videos.

For a deeper dive into the architecture, consult our [Design Documentation](docs/design.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Contributing

We welcome contributions from the community! Please review our [Contribution Guidelines](CONTRIBUTING.md) to get started.

## Feedback and Support

If you encounter issues or have any questions, feel free to [open an issue](https://github.com/yourusername/dancetube/issues) or reach out to us in the [DanceTube Discord Community](https://discord.gg/).

---

Thank you for choosing DanceTube! Get ready to dance and share your passion with the world.
