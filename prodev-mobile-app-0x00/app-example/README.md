When I ran the reset command:

npm run reset-project

I chose Y to move existing files instead of deleting them.
The following actions were performed automatically:

📁 A new folder named /app-example was created.

The following folders were moved into /app-example for backup:

/app

/components

/hooks

/constants

/scripts

📁 A new /app directory was created from scratch.

📄 Fresh files app/index.tsx and app/\_layout.tsx were generated.

✅ Reset completed successfully.

After the reset, the terminal displayed:

✅ Project reset complete. Next steps:

1. Run `npx expo start` to start a development server.
2. Edit app/index.tsx to edit the main screen.
3. Delete the /app-example directory when you're done referencing it.

Summary:
The reset command backed up my old files into /app-example and recreated a clean Expo Router structure with a new /app folder. None of my previous work was lost — everything was safely moved.
