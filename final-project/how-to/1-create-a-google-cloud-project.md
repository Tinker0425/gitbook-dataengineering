# 1 - Create a Google Cloud Project

💡 Review GCP Setup from the course if needed [here](https://github.com/DataTalksClub/data-engineering-zoomcamp/blob/main/01-docker-terraform/1_terraform_gcp/2_gcp_overview.md)

1. **Sign in to Google Cloud Console**:
   * Visit the [Google Cloud Console](https://console.cloud.google.com/).
   * Sign in with your Google account. If you don't have one, you will need to create an account.
2. **Create a Google Cloud Project**:
   * If you don't have a project yet, you'll need to create one.
     1. In the Cloud Console, click on the **project drop-down** at the top of the page.
     2. Click **New Project**.
     3. Name your project `PetFinderAPI`
     4. Click **Create**.
3.  **Enable Google Cloud Storage API**:

    * In the Cloud Console, navigate to the **APIs & Services** > **Library**.
    * Search for **Google Cloud Storage** in the search bar and select **Google Cloud Storage JSON API**.
    * Click **Enable** to enable the API for your project.

    <figure><img src="../../.gitbook/assets/Screen Shot 2025-03-24 at 6.03.34 PM.png" alt=""><figcaption></figcaption></figure>
4. **Create a Service Account**:
   * Navigate to **IAM & Admin** > **Service Accounts** in the Google Cloud Console.
   * Click **Create Service Account**.
     1. **Service Account Name**: Enter a name `petfinder-api-access`, create + continue
     2. **Role**: Choose **Owner**
     3. In the **Role** dropdown, select **Storage Object Admin**
     4. Click Continue & Done
   * Now you should see your service account! Click on it, and then click `Keys` tab

<figure><img src="../../.gitbook/assets/Screen Shot 2025-03-24 at 6.05.47 PM.png" alt=""><figcaption></figcaption></figure>

* **Add Key** - **Create New Key**, select **JSON**. This will generate a key file that you'll download
* Click **Create** and save the downloaded JSON key to a secure location on your machine. :warning: - **Service Account Key**: Keep the service account JSON file secure and DO NOT add it to github.

❗ I recommend keeping up your cloud browser
