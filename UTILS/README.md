# Utils

This folder contains some quick snippets.

## Quickstart

Each folder contains specific instructions for the corresponding example.

## Examples

* **Add Labels (Java)**: how to add labels (in code) to the job in order to track expenses in the Billing Export.
* **BigQuery Null Values (Java)**: how to write records with `Null` values to BigQuery using Dataflow.
* **BigQuery Results to CSV (Python)**: how to write BigQuery results to GCS in CSV format.
* **BigQuery Upsert Rows (Java)**: how to use DML to update a BigQuery table once a Dataflow job finishes writing data.
* **Corrupt Zip Match (Java)**: how to catch which file throws an exception when reading glob matches.
* **Dynamic BigQuery Writes (Java + Python)**: how to write to different BigQuery tables according to data.
* **Enrich with BigQuery (Java)**: how to read BigQuery data within an intermediate step to enrich an existing PCollection.
* **FileIO Custom Naming (Python)**: how to use a function to control how output files are named.
* **Flatten Side Outputs (Java)**: how to get elements belonging to different side outputs.     
* **Input Filenames (Java)**: how to process files according to their format (i.e. CSV or XML).
* **Longest Row (Python)**: how to find the record with more words in a file using the `Top` transform.
* **Map Elements (Java)**: how to apply the `MapElements` transform.
* **Map vs ParDo (Python)**: how to call the same function with `Beam.Map` and `Beam.ParDo`.
* **Multiple Topics (Java)**: pass as input option a comma-separated list of Pub/Sub topics.
* **One Row, One File (Java)**: write each row/record to a different output file.
* **One Window, One File (Python)**: write elements from each window to a different output file.
* **Pub/Sub get attribute (Java)**: how to retrieve a message attribute.
* **Pub/Sub notifications (Python)**: how to process data that has just been uploaded to GCS.
* **Pub/Sub publish time (Java)**: how to get message publish time in Dataflow.
* **Pub/Sub and Windowing (Scala)**: testing streaming pipelines with Spotify's Scio.
* **Retrieve Job ID (Python)**: how to retrieve the Job ID from within the job pipeline.
* **Re-windowing (Python)**: how to apply a global window to elements that are already windowed.
* **Schema in GCS file (Python)**: how to use a GCS-hosted schema to enrich data in our pipeline.
* **SHA-256 (Java)**: how to calculate SHA-256 Hash of each file.
* **Sign GCS Blob (Python)**: how to pass credentials to GCS Client as a side input.
* **Stop Job (Python)**: how to programmatically stop a Dataflow job using the Python Google API Client Library.
* **Understanding Wall Time (Java)**: quick idea to visualize wall time.
* **Which SDK? (Python)**: how to retrieve the list of jobs with specific SDK versions.

## License

These examples are provided under the Apache License 2.0.

## Issues

Report any issue to the GitHub issue tracker.
