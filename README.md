# Minimum Static HTML

## Running the project locally

If you want to test your project locally, you can use the following commands:

```bash
# Starts the replica, running in the background
dfx start --background

# Deploys your canisters to the replica and generates your candid interface
dfx deploy
```

Once the job completes, your application will be available at `http://{asset_canister_id}.localhost:8000`.

The asset canister id can be found as the following command:

```bash
dfx canister id test_assets
```
