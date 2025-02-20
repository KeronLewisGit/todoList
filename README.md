 # To-Do List App

This is a simple **To-Do List** application built with **React Native** using **Expo**. It allows users to add and remove tasks in a minimal, user-friendly interface.

## Features

- Add tasks to the list
- Delete tasks by tapping on them
- Simple and clean UI
- Uses React Hooks (`useState`)
- Dismisses keyboard on task addition
- Works on Android, iOS, and Web

## Installation & Setup

### Prerequisites
- Install [Node.js](https://nodejs.org/) and [Expo CLI](https://docs.expo.dev/get-started/installation/).

### Steps to Run
```bash
# Clone this repository
git clone https://github.com/KeronLewisGit/todoList.git
cd todoList

# Install dependencies
npm install

# Start the app
npm start
```
```
This will launch Expo, allowing you to run the app on an emulator, a real device, or in a browser.

## Project Structure

/todoList
├── components/       # Custom React components (e.g., Task.js)
├── assets/           # Static assets (e.g., images, icons)
├── App.js            # Main app logic
├── index.js          # Entry point
├── package.json      # Dependencies and scripts
├── .gitignore        # Ignored files in version control
└── app.json          # Expo configuration


## Dependencies
- `react-native`: 0.76.7
- `react`: 18.3.1
- `expo`: ~52.0.36
- `expo-status-bar`: ~2.0.1

## How to Use
1. Enter a task in the text field.
2. Tap the "Add" button to add the task.
3. Tap a task to remove it from the list.

## Contributing
Feel free to fork the repository and submit pull requests with improvements!

## License
This project is open-source and free to use.