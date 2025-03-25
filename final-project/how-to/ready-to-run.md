---
icon: person-running-fast
---

# Ready to Run!

1. **Github Actions Run Terraform** ⚠️ for initial set-up only!!

<figure><img src="../../.gitbook/assets/Screen Shot 2025-03-24 at 6.34.37 PM.png" alt=""><figcaption></figcaption></figure>

* Go to Github Actions in your repo
* Go to `Teraform GCP Deployment`
* Click `Run workflow` -> `Run workflow`
* You can then click on the event and the run to look at details
* Once it completes ✅ Go to Google cloud and check:
  1. Bucket named `petfinderapi-petfinder-data`
  2. BigQuery database named `petfinderapi / petfinder_data`

1. **Github Actions Daily Python Run** ⚠️ The cron job is commented out in the yml file. If you would like it to run daily, go to \`\` and uncomment the cron line
   * Go to Github Actions in your repo
   * Go to `Fetch and Upload PetFinder Data`
   * Click `Run workflow` -> `Run workflow`
   * You can then click on the event and the run to look at details
   * Once it completes ✅ Go to Google cloud and check:
     1. A csv with today's date was added to your bucket
     2. `raw_petfinder` data in your BigQuery for today's petfinder values!
2. **Github Actions Daily DBT** ⚠️ The cron job is commented out in the yml file. If you would like it to run daily, go to \`\` and uncomment the cron line
   * Go to Github Actions in your repo
   * Go to `Run dbt Transformations`
   * Click `Run workflow` -> `Run workflow`
   * You can then click on the event and the run to look at details
   * Once it completes ✅ Go to Google cloud and check in BigQuery:
     1. Created 'active\_pets', 'stg\_petfinder', and partitioned and clustered 'transformed\_petfinder'
