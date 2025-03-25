# 3 - Clone/Fork This Repo in Github

<figure><img src="../../.gitbook/assets/Screen Shot 2025-03-24 at 6.23.05 PM.png" alt=""><figcaption></figcaption></figure>

1. **Fork/Clone the repository**:
   * Fork it to your GitHub account.
   * This is mandatory, as I use Github Actions for Workflow

<figure><img src="../../.gitbook/assets/Screen Shot 2025-03-24 at 6.24.05 PM.png" alt=""><figcaption></figcaption></figure>

1.  **Set up secrets**:

    * Go to the repository's **Settings** > **Secrets and variables** > **Actions**.



    <figure><img src="../../.gitbook/assets/Screen Shot 2025-03-24 at 6.25.34 PM.png" alt=""><figcaption></figcaption></figure>

    * Add the following secrets:
      * `GCS_CREDENTIALS`: Google Cloud credentials file (as a JSON string).
      * `PETFINDER_CLIENT_SECRET`: PetFinder API key.
      * `PETFINDER_CLIENT_ID`: PetFinder API ID.
      * `BUCKET`: Global unique bucket name (example petfinder-bucket-5987654)



    <figure><img src="../../.gitbook/assets/Screen Shot 2025-03-24 at 6.27.40 PM.png" alt=""><figcaption></figcaption></figure>
