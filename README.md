
# RUREDU

An open-source platform to share PDF notes for educational institutions because sharing is caring! 


## Run Locally

Clone the project

```bash
  git clone https://github.com/your-username/Ruredu.git
```

Go to the project directory

```bash
  cd Ruredu
```

Install dependencies

```bash
  cd client
  npm install
  cd ..
  cd server
  npm install
```

Start the frontend server

```bash
  cd client
  npm run dev
```

Start the backend server

```bash
  cd server
  nodemon index.js
  nodemon server.js
```
## Features 🚀

- **Student Side:** Manage notes more efficiently based on subject unit categorisation 🎉
- **Admin Side:** Because only admins can handle the sacred task of adding notes. 👑
- **Admin Powers:** Grant access to others to become admins. Beware of the power you wield! ⚡
- **Task Monitoring:** Keep an eye on those pending tasks, mark them completed, feel accomplished. 📝✅
## Structure 🏗️

- Subjects ➡️ Units ➡️ Topics ➡️ Notes
  Because who needs a straightforward hierarchy?

## User Profile 👤

- Update your username and password. Forget them again. Repeat. ♻️

## Challenges Faced (in a totally professional manner) 🤦‍♂️

1. Spent a day figuring out an Axios error . Figured out that it was an proxy error and fixed it by adding full URL - http://localhost:5000/api/... because why not? It worked like a charm! 😅

2. Fedora doesn't support mongosh, had to resort to MongoDB Atlas. Fedora, you let me down. 🐧

3. IP address changes mean server stops. MongoDB only allows connected IPs. Cue the sudden existential crisis. 🌐

4. Wrestling with nested objects in the subject model. Three layers deep, like an onion. Cried a little. 😢

## Credits 🙌

Huge shoutout to ChatGPT! It wrote most of my code, even this README. Yeah, I'm practically an AI assistant myself. 🤖

## Noob Chronicles 🤓

- Still can't tell the difference between PUT and POST. It's like asking me to differentiate between a cat and a dog. 😅

- Arrow functions? Async functions? Eh, who needs them? I'm a prompt engineer. I can make it work, even if I don't understand how. 🛠️

## Contributing 🤝

Contributions are welcome! This might be one of the quirkiest projects you've ever seen . If you're a beginner, it's a golden opportunity to dive into the chaos and fix things! ✨

## License 📜

This project is licensed under the [MIT LICENSE]. Remember, sharing code is cool, just like sharing notes! 🚀✨



[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
