# Apache MADlib (apache-madlib)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Apache MADlib is an open-source library for scalable in-database analytics. It provides data-parallel implementations of mathematical, statistical, and machine learning methods for structured and unstructured data, executed within PostgreSQL or Greenplum Database. MADlib enables data scientists to run machine learning algorithms directly in the database using SQL.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-madlib/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - In-Database Analytics, Machine Learning, PostgreSQL, SQL, Statistics, Deep Learning

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache MADlib
MADlib provides SQL-callable functions for classification, regression, clustering, dimensionality reduction, graph analytics, time series analysis, deep learning with Keras/TensorFlow backend, and other machine learning algorithms running directly within PostgreSQL or Greenplum Database with GPU acceleration support.

**Human URL:** [https://madlib.apache.org/docs/latest/index.html](https://madlib.apache.org/docs/latest/index.html)

#### Tags:

 - Machine Learning, PostgreSQL, SQL, Deep Learning, Statistics

#### Properties

- [Documentation](https://madlib.apache.org/docs/latest/index.html)
- [GettingStarted](https://cwiki.apache.org/confluence/display/MADLIB/Installation+Guide)
- [GitHubRepository](https://github.com/apache/madlib)

## Common Properties

- [Portal](https://madlib.apache.org/)
- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/madlib)
- [Wiki](https://cwiki.apache.org/confluence/display/MADLIB/)
- [IssueTracker](https://issues.apache.org/jira/browse/MADLIB)
- [TermsOfService](https://www.apache.org/licenses/LICENSE-2.0)

## Features

| Name | Description |
|------|-------------|
| In-Database Machine Learning | Run machine learning algorithms directly within PostgreSQL or Greenplum Database using SQL, eliminating data movement overhead. |
| Classification and Regression | Support for logistic regression, linear regression, naive Bayes, decision trees, random forests, support vector machines, and more. |
| Clustering Algorithms | K-Means, DBSCAN, and other clustering algorithms for unsupervised learning within the database. |
| Deep Learning with Keras/TensorFlow | Train and serve deep learning models using Keras and TensorFlow backends with GPU acceleration support. |
| Graph Analytics | Built-in graph algorithms for network analysis, path finding, and community detection on graph data stored in the database. |
| Time Series Analysis | ARIMA, SARIMA, and other time series forecasting models running in-database. |
| Dimensionality Reduction | PCA and SVD implementations for dimensionality reduction and feature extraction. |
| Model Selection and Hyperparameter Tuning | Cross-validation and hyperparameter optimization frameworks for model selection. |
| Association Rules | FP-Growth and Apriori algorithms for market basket analysis and association rule mining. |

## Use Cases

| Name | Description |
|------|-------------|
| Predictive Analytics | Build predictive models for churn prediction, fraud detection, and demand forecasting directly on database data. |
| Recommendation Systems | Implement collaborative filtering and content-based recommendation algorithms using in-database machine learning. |
| Customer Segmentation | Cluster customers using K-Means and other algorithms to identify segments for targeted marketing. |
| Anomaly Detection | Detect anomalies in time series and transactional data using statistical models running in-database. |
| Network Analysis | Analyze social networks, supply chains, and communication graphs using built-in graph algorithms. |

## Integrations

| Name | Description |
|------|-------------|
| PostgreSQL | Primary execution environment supporting PostgreSQL versions 11 through 15. |
| Greenplum Database | Native support for Greenplum Database GP6 and GP7 for massively parallel processing. |
| TensorFlow | Deep learning backend integration for training neural networks within the database. |
| Keras | High-level deep learning API integration for building and training models with GPU acceleration. |
| XGBoost | Gradient boosting framework integration for high-performance tree-based models. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
