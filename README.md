# Todoey ✓

## Our Goal

The objective of this tutorial is to understand how to manage state in Flutter. We'll look at various Flutter architecture choices and learn to use the officially recommended Provider package to manage our app state.

## What you will create

A todolist app to keep track of all your tasks.

## What you will learn

- Understand what is state and why we need to manage it.
- Understand the difference between ephemeral (local) state and app state.
- See the problems with simply relying on setState().
- Learn about the concept of Prop Drilling.
- Examine various popular ways of managing app state for Flutter projects.
- Learn about the List Builder.
- Use the Flutter BottomSheet Widget.
- Learn to lift state up to be able to access it from children widgets.
- Learn about design patterns and why they are useful.
- Understand how the Provider package works and use it to manage app state.

## Getting Started

To run the Furniture Marketplace Application project locally, follow these steps:

1. Clone the repository: `git clone git@github.com:Asad-Abbas-Coder/Todo_Flutter.git`
2. Open the project in your preferred IDE or code editor.
3. Ensure you have Flutter SDK installed.
4. Run `flutter pub get` to fetch the project dependencies.
5. Connect a device or start an emulator/simulator.
6. Run `flutter run` to launch the application.

## Architecture

This project is based on the Clean Architecture principles, which aim to create a scalable and maintainable codebase. The core architecture consists of three layers: presentation, domain, and data, providing separation of concerns and testability.

## Contributing

Contributions are welcome! Please follow the steps below to contribute:

1. Fork the repository.

2. Create a new branch:

    ```bash
        git checkout -b your-feature-branch
    ```

3. Commit your changes:

    ```bash
        git commit -m "Add your detailed message"
    ```

4. Push to the branch:

    ```bash
        git push origin your-feature-branch
    ```

5. Create a merge request for **dev** branch and assign the reviewer

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this project as per the terms of the license.
