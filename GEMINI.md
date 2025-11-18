# Project Overview

This is a mobile application built with [Expo](https://expo.dev), a framework for building universal React applications. The project is a clone of the Uber app, and it uses [React Native](https://reactnative.dev/) to create a native user experience for both Android and iOS.

The project is structured using file-based routing with [Expo Router](https://docs.expo.dev/router/introduction/). It utilizes [Tailwind CSS](https://tailwindcss.com/) for styling, integrated with React Native through [NativeWind](https://www.nativewind.dev/). The app supports both light and dark modes.

## Building and Running

To get started with the project, follow these steps:

1.  **Install dependencies:**

    ```bash
    npm install
    ```

2.  **Start the app:**

    You can run the app on different platforms using the following commands:

    *   To start the development server and see the available options, run:

        ```bash
        npx expo start
        ```

    *   To run on Android, use:

        ```bash
        npm run android
        ```

    *   To run on iOS, use:

        ```bash
        npm run ios
        ```

    *   To run on the web, use:

        ```bash
        npm run web
        ```

3.  **Linting:**

    To check the code for any linting errors, run:

    ```bash
    npm run lint
    ```

## Development Conventions

*   **Styling:** The project uses Tailwind CSS with NativeWind for styling. Utility classes are preferred over creating custom stylesheets.
*   **Routing:** The app uses file-based routing with Expo Router. New screens can be created by adding files to the `app` directory.
*   **Components:** Reusable components are placed in the `components` directory.
*   **Theme:** The app supports both light and dark modes. Theme-related constants are defined in `constants/theme.ts`.
*   **Hooks:** Custom hooks are located in the `hooks` directory.
