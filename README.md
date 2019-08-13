# A simple Flutter Web project 
### Configured for VS Code Development Container mode

This is the hello world sample project of Flutter Web that you can execute with **[VS Code Remote - Containers](https://aka.ms/vscode-remote/containers)** extension in few easy steps.

## Setting up the development container

Follow these steps to open this sample in a container:

1. If this is your first time using a development container in Visual Studio Code, please follow the [getting started steps](https://aka.ms/vscode-remote/containers/getting-started).

2. If you're not yet in a development container:
   - Clone this repository.
   - Press <kbd>F1</kbd> and select the **Remote-Containers: Open Folder in Container...** command.
   - Select the cloned copy of this folder, wait for the container to start, and try things out!

## Things to try

One you have this sample opened in a container, you'll be able to work with it like you would locally.

Some things to try:

1. **Edit:**
   - Open `lib/main.dart`
   - Try adding some code and check out the language features. Notice that `dart.dart` and the `dart.flutter` extensions are already installed in the container.
2. **Terminal:** Press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>\`</kbd> and type `uname` and other Linux commands from the terminal window.
3. **Run with auto reload:**
   - Open container terminal and, inside /workspace folder, type: `livecode` (it's a bash alias executing `flutter packages pub global run webdev serve --hostname 0.0.0.0 --auto restart`)
   - Open a local browser and go to `http://localhost:8080` and note you can connect to the server in the container.

## TODO

Add git configuration to work inside container