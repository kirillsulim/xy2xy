# xy2xy
A list of technologies similar to inner Yandex technologies.

This repository inspired by [xg2xg](https://github.com/jhuangtw-dev/xg2xg).


## For who is this file?

This file may be good for experienced developers who:

1. Starts to working at Yandex. In that case this document helps you translate architecture based for example on Kafka and Airflow to Logbroker and Nirvana.
2. Leave Yandex. In that case this document helps you translate architecture based for example on Logbroker and Nirvana to Kafka and Airflow.
3. Just want to see a list of "big guns".


## Core technoogies

<table>
  <tr>
    <th>Technology</th>
    <th>Yandex internal</th>
    <th>Analogs</th>
  </tr>
  <tr>
    <!-- Technology --><td>Version control system</td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/482926/">arc</a></td>
    <!-- Analogs --><td>
      <a href="https://git-scm.com/">git</a> (Open source)<br/>
      <a href="https://subversion.apache.org/">svn</a> (Open source)<br/>
      <a href="https://www.perforce.com/">perforce</a> (Commercial)
    </td>
  </tr>
  <tr>
    <!-- Technology --><td>Build tool</td>
    <!-- Yandex internal --><td><a href="https://github.com/yandex/CMICOT/blob/master/ya">ya make</a></td>
    <!-- Analogs --><td>
      <a href="https://cmake.org/">CMake</a> (Open source)<br/>
      <a href="https://bazel.build/">Bazel</a> (Open source)<br/>
    </td>
  </tr>
</table>


## Data bases and data processing

<table>
  <tr>
    <th>Technology</th>
    <th>Yandex internal</th>
    <th>Analogs</th>
  </tr>
  <tr>
    <!-- Technology --><td>Map-reduce</td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/311104/">YT</a></td>
    <!-- Analogs --><td><a href="https://hadoop.apache.org/">Hadoop</a> (Open source)</td>
  </tr>
  <tr>
    <!-- Technology --><td>Querry language over map-reduce</td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/312430/">YQL</a></td>
    <!-- Analogs --><td><a href="https://hive.apache.org/">Hive</a> (Open source)</td>
  </tr>
  <tr>
    <!-- Technology --><td>Column oriented database</td>
    <!-- Yandex internal --><td><a href="https://clickhouse.tech/">ClickHouse</a></td>
    <!-- Analogs --><td><a href="https://clickhouse.tech/">ClickHouse</a> (Open source by Yandex)</td>
  </tr>
  <tr>
    <!-- Technology --><td>Workflow manager</td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/351016/">Nirvana</a></td>
    <!-- Analogs --><td><a href="https://airflow.apache.org/">Airflow</a> (Open source)</td>
  </tr>
  <tr>
    <!-- Technology --><td>Message broker</td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/239823/">Logbroker</a></td>
    <!-- Aanalogs --><td><a href="https://kafka.apache.org/">Kafka</a> (Open source)</td>
  </tr>
</table>


## Machine learning

<table>
  <tr>
    <th>Technology</th>
    <th>Yandex internal</th>
    <th>Analogs</th>
  </tr>
  <tr>
    <!-- Technology --><td>Simple tasks outsoursing</td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/305956/">Toloka</a>
    <!-- Analogs --><td>
      <a href="https://toloka.yandex.ru/">Toloka</a> (Commercial by Yandex)<br/>
      <a href="https://www.mturk.com/">Amazon Mechanical turk</a> (Commecial by Amazon)
    </td>
  </tr>
  <tr>
    <!-- Technology --><td>Gradient boosting library</td>
    <!-- Yandex internal --><td><a href="https://catboost.ai/">CatBoost</a></td>
    <!-- Analogs --><td>
      <a href="https://catboost.ai/">CatBoost</a> (Open source by Yandex)<br/>
      <a href="https://github.com/dmlc/xgboost">XGBoost</a> (Open source)<br/>
      <a href="https://github.com/microsoft/LightGBM">LightGBM</a> (Open source by Microsoft)
    </td>
  </tr>
</table>


## Management

<table>
  <tr>
    <th>Technology</th>
    <th>Yandex internal</th>
    <th>Analogs</th>
  </tr>
  <tr>
    <!-- Technology --><td>Issue tracker</td>
    <!-- Yandex internal --><td><a href="https://yandex.ru/tracker/">Tracker</a></td>
    <!-- Analogs --><td>
      <a href="https://yandex.ru/tracker/">Tracker</a> (Commecial by Yandex)<br/>
      <a href="https://www.atlassian.com/software/jira">Jira</a> (Commecial by Atlassian)
    </td>
  </tr>
  <tr>
    <!-- Technology --><td>Wiki engine</td>
    <!-- Yandex internal --><td><a href="https://connect.yandex.ru/?noredirect=">Wiki</a></td>
    <!-- Analogs --><td>
      <a href="https://connect.yandex.ru/?noredirect=">Wiki</a> (Commecial by Yandex)<br/>
      <a href="https://www.mediawiki.org/">Mediawiki</a> (Open source)<br/>
      <a href="https://www.atlassian.com/software/confluence">Confluence</a> (Commecial by Atlassian)
    </td>
  </tr>
</table>


## Contibuting

Feel free to add any technologies.
If you add internal Yandex technology, you must provide link that prooves this technology is not under NDA.
Usually this is link to [official Yandex blog on habr.com](https://habr.com/ru/company/yandex/) or link to [official Yandex GitHub repository](https://github.com/yandex).

## Why HTML in .md?

Big markdown tables are messy. Big html tables are just a little less messy, so I choosed html.
