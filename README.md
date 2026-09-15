# Code Companion

Create a full-stack web application called "Universal Code Debugger".

Goal:

A web app where users can paste code in different programming languages and get debugging help, error explanations, and suggested fixes.

Core Features:

1. Code Editor

- Use Monaco Editor or CodeMirror

- Syntax highlighting

- Language selector (Python, JavaScript, C, C++, Java, Go, Rust, PHP)

2. Code Execution

- Run the code securely in a sandbox environment

- Show console output and errors

3. Debugging System

- Detect syntax errors and runtime errors

- Show line numbers where the error occurs

- Provide explanation of the error

- Suggest fixed code

4. AI Debug Assistant

- When an error occurs, analyze the code and error

- Explain the bug in simple terms

- Provide a corrected version of the code

5. UI

- Modern interface

- Dark/light mode

- Split layout:

  Left side → code editor

  Right side → output + debugging explanation

Tech Stack:

Frontend:

- React

- Tailwind CSS

- Monaco Editor

Backend:

- Node.js with Express

Execution Engine:

- Use Docker containers or isolated sandboxes to run code safely

API Routes:

POST /run

→ runs the code

POST /debug

→ returns debugging explanation and suggested fix

Security:

- Prevent infinite loops

- Time limit for execution

- Memory limits

Extra Features:

- Save snippets

- Share debug sessions

- Download corrected code

Deliverables:

1. Full project structure

2. Frontend + backend code

3. Instructions to run the app

4. Example debugging workflow

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://aicode-debugger.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/a9db50c2-7201-43ad-b04d-53a99abad69c).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
