# airflow-providers-oraclethick

Provider for Oracle DB for Airflow 2.X. Just initializes thick client.
Creates connection type OracleThick.


Build and install locally:

```
python3 -m build

pip install airflow-providers-oraclethick-hook --no-index --find-links file:///<path>/git/airflow_provider_oracle_thick/dist/
```

Start airflow:

```
airflow webserver
```

Check if provider is registered and if new connection type has appeared.

Install:

```
pip install airflow-providers-oraclethick-hook
```