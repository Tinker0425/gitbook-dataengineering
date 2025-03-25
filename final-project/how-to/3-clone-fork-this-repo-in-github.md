# 3 - Clone/Fork This Repo in Github

1. **Fork/Clone the repository**:
   * Fork it to your GitHub account.
   * This is mandatory, as I use Github Actions for Workflow
2. **Set up secrets**:
   * Go to the repository's **Settings** > **Secrets and variables** > **Actions**.
   * Add the following secrets:
     * `GCP_CREDENTIALS`: Google Cloud credentials file (as a JSON string).
     * `PETFINDER_API_KEY`: PetFinder API key.
     * `PETFINDER_API_ID`: PetFinder API ID.
