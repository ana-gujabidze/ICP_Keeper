# Keeper project (React.js + ICP)

Welcome to DKeeper project! This project is similar to this [Keeper](https://github.com/ana-gujabidze/Reactjs_Keeper) project, but here back-end is implemented using Motoko language.
Unlike the previous Keeper project, which covers only front-end, in this one added notes is kept permanently and does not disappear upon refreshing the page.

To learn more before you start working with dbank, see the following documentation available online:

- [Quick Start](https://sdk.dfinity.org/docs/quickstart/quickstart-intro.html)
- [SDK Developer Tools](https://sdk.dfinity.org/docs/developers-guide/sdk-guide.html)
- [Motoko Programming Language Guide](https://sdk.dfinity.org/docs/language-guide/motoko.html)
- [Motoko Language Quick Reference](https://sdk.dfinity.org/docs/language-guide/language-manual.html)
- [JavaScript API Reference](https://erxue-5aaaa-aaaab-qaagq-cai.raw.ic0.app)
---
## Common Usage
The app allows to:
- add new notes which are chronologically ordered
- delete notes

---
## Requirements
- Node 16
- Git
- DFX
---
## Common setup
If you want to start working on the project right away, try the following commands:

```bash
git clone https://github.com/ana-gujabidze/ICP_Keeper.git
cd ICP_Keeper/
dfx help
dfx config --help
```

## Running the project locally

Run the project locally, use the following commands:

```bash
# Starts the replica, running in the background
dfx start --background

# Deploys your canisters to the replica and generates your candid interface
dfx deploy
```

Once the job completes, application will be available at `http://localhost:8000?canisterId={asset_canister_id}`.

Additionally, to see frontend changes, start a development server with

```bash
npm start
```

Which will start a server at `http://localhost:8080`, proxying API requests to the replica at port 8000.
