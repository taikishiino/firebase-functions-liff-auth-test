# firebase-functions-liff-auth-test

## Setup
- Firebase（Blazeプラン）
- LIFF

```bash
$ firebase init                                                                                                                                                                                         20-12-13, 1:58:08

     ######## #### ########  ######## ########     ###     ######  ########
     ##        ##  ##     ## ##       ##     ##  ##   ##  ##       ##
     ######    ##  ########  ######   ########  #########  ######  ######
     ##        ##  ##    ##  ##       ##     ## ##     ##       ## ##
     ##       #### ##     ## ######## ########  ##     ##  ######  ########

You're about to initialize a Firebase project in this directory:

  /Users/taiki.shiino/organizations/private/repositories/work/firebase-functions-liff-auth_customToken

? Which Firebase CLI features do you want to set up for this folder? Press Space to select features, then Enter to confirm your choices. Functions: Configure and deploy Cloud Functions, Emulators: Set up local emulators for Firebase features, Remote Conf
ig: Get, deploy, and rollback configurations for Remote Config

=== Project Setup

First, let's associate this project directory with a Firebase project.
You can create multiple project aliases by running firebase use --add,
but for now we'll just set up a default project.

? Please select an option: Use an existing project
? Select a default Firebase project for this directory: liff-test-a23bd (LIFF-TEST)
i  Using project liff-test-a23bd (LIFF-TEST)

=== Functions Setup

A functions directory will be created in your project with a Node.js
package pre-configured. Functions can be deployed with firebase deploy.

? What language would you like to use to write Cloud Functions? TypeScript
? Do you want to use ESLint to catch probable bugs and enforce style? Yes
? File functions/package.json already exists. Overwrite? No
i  Skipping write of functions/package.json
? File functions/.eslintrc.js already exists. Overwrite? No
i  Skipping write of functions/.eslintrc.js
? File functions/tsconfig.json already exists. Overwrite? No
i  Skipping write of functions/tsconfig.json
? File functions/src/index.ts already exists. Overwrite? No
i  Skipping write of functions/src/index.ts
? File functions/.gitignore already exists. Overwrite? No
i  Skipping write of functions/.gitignore
? Do you want to install dependencies with npm now? Yes

audited 405 packages in 4.573s
found 0 vulnerabilities


=== Emulators Setup
? Which Firebase emulators do you want to set up? Press Space to select emulators, then Enter to confirm your choices. (Press <space> to select, <a> to toggle all, <i> to invert selection)Functions Emulator
? Which port do you want to use for the functions emulator? 5001
? Would you like to enable the Emulator UI? Yes
? Which port do you want to use for the Emulator UI (leave empty to use any available port)?
? Would you like to download the emulators now? No

=== Remoteconfig Setup
? What file should be used for your Remote Config template? remoteconfig.template.json

i  Writing configuration info to firebase.json...
i  Writing project information to .firebaserc...
i  Writing gitignore file to .gitignore...

✔  Firebase initialization complete!
```
