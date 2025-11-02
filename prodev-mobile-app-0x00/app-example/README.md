# My First Mobile App - Setup Journal

This file documents the steps for creating and testing my first Expo application.

## Steps Followed for Scaffolding

1.  Created a new directory for this task: `prodev-mobile-app-0x00`.
2.  Navigated into it: `cd prodev-mobile-app-0x00`.
3.  Ran `npx create-expo-app@latest app-example` to create the project inside a folder named `app-example`.
4.  Edited the `app-example/app/(tabs)/index.tsx` file to change the main text.

## Testing the Application

I ran `npx expo start` from the `app-example` directory and scanned the QR code with the Expo Go app on my phone. The app loaded successfully and displayed my new text, "First App Created".

## Observations from the `npm run reset-project` Command

After stopping the server, I ran the `npm run reset-project` command.

Based on my terminal output, this command is an alias for **`npx expo start --clear`**.

This command re-starts the development server but also tells Expo to **clear the project's cache** before starting. This is extremely useful for fixing problems where old code or data (like a failed download) gets "stuck," and a simple restart doesn't fix it. It's like a "hard refresh" for the entire project.
