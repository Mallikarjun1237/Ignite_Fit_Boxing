# AK Boxing Club

The full source code for the AK Boxing Club website.

## Open and run in VS Code

1. Install [Bun](https://bun.sh/) if it is not already installed.
2. Extract this ZIP and open the `AK-Boxing-Club` folder in VS Code.
3. Open VS Code's terminal in that folder and run:

   ```sh
   bun install
   bun run dev
   ```

4. Open the local address printed in the terminal.

## Notes

- This project uses TanStack Start, React, TypeScript, Tailwind CSS, and Vite.
- Booking information is currently demo-only and is saved in the visitor's browser storage; there is no shared database connected.
- Do not copy `node_modules` from another computer. `bun install` creates the local dependencies from the included manifest and lockfile.
