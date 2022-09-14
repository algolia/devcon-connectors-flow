# Algolia DevCon 2022: Connectors & Flow
Learn more about Connectors & Flow and share your feedback!

## Why are we building these APIs?
We want to make it as easy as possible to get data into Algolia. Today, we offer a variety of methods and APIs for data ingestion, however:
- Using our APIs is extremely flexible but you might need a developer.
- Algolia offers API-first tooling but you might need to set up new services.
- Algolia is schemaless but your data might need to be prepped before ingestion.

Our new Connector and Flow APIs will make all of the above easier by handling your data fetching and processing for you!

## Connector APIs
The Connector APIs provide the ability to define a data source you want to bring into Algolia. By providing us credentials and configuration settings you will allow Algolia to fetch and sync your data for you. The Connector APIs are made up of four parts:
- **Authentication**: Credential information to access data on your behalf.
- **Source**: Information on how to get data, ex: table name, object type, pricing strategy, etc. Links to a specific authentication.
- **Destination**: An index or any other Algolia product, ex: Recommend, Insights API.
- **Task**: A coupling of a Source, Destination, and a trigger. Trigger can be on schedule, on event (ex: webhook), or manual.

## Flow APIs
The Flow APIs provide a way to prep and enhance your data as it is ingested into Algolia. As your data is ingested you will be able to do things like filter, transform, clean and enrich by pulling in external data. The Flow APIs are made up of two parts:
- **Steps**: Individual transformation steps that process data.
- **Flows**: A string of steps put together to create a complete data processing pipeline.

## We need you!
As we continue to build our Connector and Flow APIs we need your input to help us determing what to build. Fill out the survey's in the [Discussions](https://github.com/algolia/devcon-connectors-flow/discussions) area to let us know what data you connect to and how you prep it!

## Stay in the know
Want to get the latest updates on these APIs and access the beta? [Sign up for our beta program](https://forms.gle/Ei3AUDgpbu8QaHtFA) and we'll let you know when it's ready!
