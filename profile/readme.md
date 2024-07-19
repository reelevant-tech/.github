
## Our product

We’re building a martech (e.g. marketing technology) product which help companies (mainly e-commerce) to generate individualized contents at scale.
Our customers store their data in our platform and use efficiently this data to generate the right content for each of their customers.

![diagram](https://user-images.githubusercontent.com/6900054/200024814-df99023f-e89d-4aaa-b468-310de8bac020.png)

Our product is divided in 4 main parts: Datasources, Workflows, Contents and Statistics. Each of those parts have different challenges.

## Technical challenges

With our **📚 Datasources** part, we should be able to retrieve, store and query any kind of data from our customers.
We're handling multiple input formats (JSON, XML, CSV, XLSX...) from multiple sources (API, SQL database, files, push...) that could weight multiples gigabytes.
The output format should be structured and easily and quickly queryable (<200ms for data sources up to billions of rows).

With our **🔗 Workflows** part, we should be able to provide a user-friendly workflow builder where they can build a valid workflow (which is a [DAG](https://en.wikipedia.org/wiki/Directed_acyclic_graph)) that will be run each time we generate a content for user.
When we execute the workflow, we expect it to be fast and reliable (<1000ms).

With our **🖼 Contents** part, we should be able to provide a user-friendly content builder (Figma like) where our customers can build multiple contents, where some content elements are variable and conditionally displayed.
When we generate a content (on-demand, when a user request a content) it should be fast (<100ms) even with large contents like GIFs and it should scale (from 10 req/s to >500 req/s in a few minutes).

With our **📈 Statistics** part, we should be able to compute (from large datasets) and display quickly right statistics to our customers.

You can see all of our jobs openings [here](https://www.welcometothejungle.com/en/companies/reelevant/jobs).
