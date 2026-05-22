### Hi there, happy to see you! 👋
---

I'm a data engineer focused on building reliable data platforms across ingestion, streaming, transformation, orchestration, and lakehouse storage.

I work with:

- Kafka/Flink pipelines for low-latency event processing
- Spark/Glue jobs for large-scale transformations
- Hudi/S3 lakehouse tables for CDC-aware analytical storage
- Airflow DAGs for orchestration, retries, freshness checks, and backfills
- SQL/dbt-style modeling for reusable analytics layers
- Data quality, schema evolution, and access governance

My work combines independent ownership with measurable business impact: cost savings, latency reduction, operational scaling, and technical debt reduction.

I care about the unglamorous parts of data engineering: stable keys, idempotent writes, partitioning, skew, small files, late events, schema drift, and making sure downstream users can trust the data.

This GitHub is where I keep personal projects, experiments, interview prep, and engineering notes around data systems, analytics engineering, and LLM-assisted workflows.

Outside of work, I enjoy building personal projects such as [Batch ETL](https://github.com/Creative-Ataraxia/GA4-Analytical-Pipeline), [Stream Processing](https://github.com/Creative-Ataraxia/eonet-realtime-streaming), and LLM-related coding competitions. I recently won a [Silver Medal](https://www.kaggle.com/certification/competitions/alexmason11/llms-you-cant-please-them-all) in a featured Kaggle LLM competition.

## Architectures I've Worked With

<table align="center">
  <tr>
    <th align="center">Governed Data Marketplace / OLAP Lakehouse</th>
    <th align="center">Realtime + Lakehouse Analytics Platform</th>
  </tr>
  <tr>
    <td align="center">
      <img src="img/1.%20Lakehouse%20Data%20Marketplace%20v4.png" width="95%" alt="Governed Data Marketplace OLAP Lakehouse Architecture"/>
    </td>
    <td align="center">
      <img src="img/2.%20Realtime%20Serving%20Lakehouse%20Analytics%20v3.png" width="95%" alt="Realtime Serving and Lakehouse Analytics Architecture"/>
    </td>
  </tr>
  <tr>
    <td valign="top">
      A governed banking data marketplace architecture coordinating historical backfills and CDC ingestion into a Spark/Glue + Hudi/S3 lakehouse, with Airflow orchestration, Lake Formation access controls, and Athena/Redshift Spectrum serving curated self-service data products.
    </td>
    <td valign="top">
      A dual-path manufacturing data platform where Kafka decouples high-volume shopfloor events, Flink/Aurora powers low-latency operational serving, and Spark/Hudi/S3 supports historical analytics and ML consumption through lakehouse storage.
    </td>
  </tr>
</table>
---

### Contacts

- Email: [roy.ma9@gmail.com](mailto:roy.ma9@gmail.com)
- LinkedIn: [linkedin.com/in/royma](https://www.linkedin.com/in/royma/)
- Visa Status: None needed — U.S. citizen and open to relocation.
