I've been enjoying Go projects along with infrastructure-related tasks such as those relating Kubernetes with GitOps. Moreover, I'm thrilled with time-series data—lately, I’ve been exploring TimescaleDB as a PostgreSQL extension with compelling results.


One gif that sums up a  where I use time-series is this one, I am able to also measure metrics from the db using pg_stat_statements, pg_stat_kcache, hypertables views and postgres_fdw:

The following GIF captures [one of my recent personal projects](https://github.com/iferdel/sensor-data-streaming-pubsub/tree/main), where I stream and store sensor data in a time-series format. Beyond ingestion, I'm also extracting meaningful database metrics using pg_stat_statements, pg_stat_kcache, hypertable views, and postgres_fdw:

![output](https://github.com/user-attachments/assets/a5c06858-825f-4465-b652-bf4dd17f96de)
