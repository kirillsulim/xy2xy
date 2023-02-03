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


## Search

<table>
  <tr>
    <th>Technology</th>
    <th>Yandex internal</th>
    <th>Analogs</th>
  </tr>
  <tr>
    <!-- Technology --><td>Content-Based Image Retrieval</td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/192404/">Siberia</a></td>
    <!-- Analogs --><td></td>
  </tr>
</table>


## Natural language processing

<table>
  <tr>
    <th>Technology</th>
    <th>Yandex internal</th>
    <th>Analogs</th>
  </tr>
  <tr>
    <!-- Technology --><td>Morphological analyzer</td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/86271/">MyStem</a></td>
    <!-- Analogs --><td>
      <a href="https://yandex.ru/dev/mystem/">MyStem</a> (Free by Yandex)<br/>
      <a href="https://github.com/natasha/natasha">Natasha</a> (Open source)
    </td>
  </tr>
  <tr>
    <!-- Technology --><td>Structured data extractor</td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/219311/">Tomita parser</a></td>
    <!-- Analogs --><td>
      <a href="https://github.com/yandex/tomita-parser/">Tomita parser</a> (Open source by Yandex)
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
    <!-- Yandex internal --><td>
      <a href="https://habr.com/ru/company/yandex/blog/189362/">Real Time MapReduce</a><br/>
      <a href="https://habr.com/ru/company/yandex/blog/311104/">YT</a>
    </td>
    <!-- Analogs --><td>
      <a href="https://hadoop.apache.org/">Hadoop</a> (Open source)<br/>
      <a href="https://spark.apache.org/">Spark</a> (Open source)
    </td>
  </tr>
  <tr>
    <!-- Technology --><td>Map-reduce cascading</td>
    <!-- Yandex internal --><td>
      <a href="https://habr.com/ru/company/yandex/blog/332688/">Nile</a>
    </td>
    <!-- Analogs --><td><a href="https://airflow.apache.org/">Airflow</a> (Open source)</td>
  </tr>
  <tr>
    <!-- Technology --><td>Querry language over map-reduce</td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/312430/">YQL</a></td>
    <!-- Analogs --><td><a href="https://hive.apache.org/">Hive</a> (Open source)</td>
  </tr>
  <tr>
    <!-- Technology --><td>Column oriented database</td>
    <!-- Yandex internal --><td><a href="https://clickhouse.tech/">ClickHouse</a></td>
    <!-- Analogs --><td>
      <a href="https://clickhouse.tech/">ClickHouse</a> (Open source by Yandex)<br/>
      <a href="https://www.vertica.com/">Vertica</a> (Commercial by Vertica)
    </td>
  </tr>
  <tr>
    <!-- Technology --><td>Workflow manager</td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/351016/">Nirvana</a></td>
    <!-- Analogs --><td>
      <a href="https://airflow.apache.org/">Airflow</a> (Open source by Apache)<br/>
      <a href="https://nifi.apache.org/index.html">NiFi</a> (Open source by Apache)<br/>
      <a href="https://github.com/n8n-io/n8n">n8n</a> (Open source) for some cases
    </td>
  </tr>
  <tr>
    <!-- Technology --><td>Message broker</td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/239823/">Logbroker</a></td>
    <!-- Aanalogs --><td><a href="https://kafka.apache.org/">Kafka</a> (Open source)</td>
  </tr>
  <tr>
    <!-- Technology --><td>Distributed key-value storage</td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/200080/">Elliptics</a></td>
    <!-- Aanalogs --><td>
      <a href="https://github.com/reverbrain/elliptics">Elliptics</a> (Open source)</br>
    </td>
  </tr>
  <tr>
    <!-- Technology --><td>Multithreaded PostgreSQL connection pool</td>
    <!-- Yandex internal --><td><a href="https://yandex.ru/dev/odyssey/">Odyssey</a></td>
    <!-- Aanalogs --><td>
      <a href="https://github.com/yandex/odyssey">Odyssey</a> (Open source by Yandex)</br>
    </td>
  </tr>
  <tr>
    <!-- Technology --><td>Distributed DataBase</td>
    <!-- Yandex internal --><td><a href="https://cloud.yandex.ru/services/ydb">Yandex Database (YDB)</a></td>
    <!-- Aanalogs --><td>
      <a href="https://cloud.yandex.ru/services/ydb">Yandex Database (YDB)</a> (Commercial by Yandex)
    </td>
  </tr>
</table>


## Frontend

<table>
  <tr>
    <th>Technology</th>
    <th>Yandex internal</th>
    <th>Analogs</th>
  </tr>
  <tr>
    <!-- Technology --><td>BEM</td>
    <!-- Yandex internal --><td><a href="https://github.com/bem/">BEM</a></td>
    <!-- Analogs --><td>
      <a href="https://github.com/bem/">BEM</a> (Open source)
    </td>
  </tr>
  <tr>
    <!-- Technology --><td>Frontend testing frameworks</td>
    <!-- Yandex internal --><td>
      <a href="https://yandex.ru/dev/gemini/">Gemini</a><br/>
      <a href="https://yandex.ru/dev/hermione/">Hermione</a><br/>
      <a href="https://yandex.ru/dev/html-elements/">HTML Elements</a>
    </td>
    <!-- Analogs --><td>
      <a href="https://github.com/gemini-testing/gemini/">Gemini</a> (Open source by Yandex)<br/>
      <a href="https://github.com/gemini-testing/hermione">Hermione</a> (Open source by Yandex)<br/>
      <a href="https://github.com/yandex-qatools/htmlelements">Html Elements</a> (Open source by Yandex)
    </td>
  </tr>
</table>


## Testing

<table>
  <tr>
    <th>Technology</th>
    <th>Yandex internal</th>
    <th>Analogs</th>
  </tr>
  <tr>
    <!-- Technology --><td>Stress testing tool</td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/202020/">Yandex Tank</a></td>
    <!-- Analogs --><td>
      <a href="https://github.com/yandex/yandex-tank">Yandex Tank</a> (Open source by Yandex)<br/>
      <a href="https://jmeter.apache.org/">JMeter</a> (Open source by Apache)<br/>
      <a href="https://gatling.io/">Gatling</a> (Open source)
    </td>
  </tr>
  <tr>
    <!-- Technology --><td>Stress testing manager</td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/202446/">Lunapark</a></td>
    <!-- Analogs --><td></td>
  </tr>
  <tr>
    <!-- Technology --><td>Testing report framework</td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/232697/">Allure</a></td>
    <!-- Analogs --><td>
      <a href="https://github.com/allure-framework/">Allure</a> (Open source)
    </td>
  </tr>
  <tr>
    <!-- Technology --><td>Java Matchers library</td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/184634/">Matchers Java</a></td>
    <!-- Analogs --><td>
      <a href="https://github.com/yandex-qatools/matchers-java">Matchers Java</a> (Open source by Yandex)<br/>
      <a href="https://github.com/hamcrest/JavaHamcrest">Hamcrest matchers</a> (Open source by Hamcrest)
    </td>
  </tr>
  <tr>
    <!-- Technology --><td>Test data generator</td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/204192/">ObjectBuilders</a></td>
    <!-- Analogs --><td>
      <a href="https://github.com/yandex-qatools/builders">ObjectBuilders</a> (Open source by Yandex)
    </td>
  </tr>
  <tr>
    <!-- Technology --><td>Microservice-oriented test framework</td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/491038/">TestSuite</a></td>
    <!-- Analogs --><td>
      <a href="https://github.com/yandex/yandex-taxi-testsuite">TestSuite</a> (Open source by Yandex)
    </td>
  </tr>
</table>


## DevOps

<table>
  <tr>
    <th>Technology</th>
    <th>Yandex internal</th>
    <th>Analogs</th>
  </tr>
  <tr>
    <!-- Technology --><td><a href="https://en.wikipedia.org/wiki/Service_mesh">Service mesh</a></td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/520134/">AppHost</a></td>
    <!-- Analogs --><td>
      <a href="https://github.com/hashicorp/consul">Consul</a> (Open source by HashiCorp)
    </td>
  </tr>
  <tr>
    <!-- Technology --><td>Microservices firewall</td>
    <!-- Yandex internal --><td><a href="https://www.youtube.com/watch?v=0Zvi6_94r5E">TVM</a></td>
    <!-- Analogs --><td>
      <a href="https://github.com/hashicorp/consul">Consul</a> (Open source by HashiCorp)
    </td>
  </tr>
  <tr>
    <!-- Technology --><td><a href="https://en.wikipedia.org/wiki/Continuous_integration">Continuous Integration</a></td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/428972/">CI</a></td>
    <!-- Analogs --><td>
      <a href="https://www.jenkins.io/">Jenkins</a> (Open source)<br/>
      <a href="https://www.jetbrains.com/teamcity/">TeamCity</a> (Commercial by JetBrains)<br/>
    </td>
  </tr>
  <tr>
    <!-- Technology --><td>Container virtualization</td>
    <!-- Yandex internal --><td><a href="https://github.com/yandex/porto">Porto</a></td>
    <!-- Analogs --><td>
      <a href="https://github.com/yandex/porto">Porto</a> (Open source by Yandex)<br/>
      <a href="https://www.docker.com/">Docker</a> (Open source)
    </td>
  </tr>
  <tr>
    <!-- Technology --><td>Iaas/PaaS</td>
    <!-- Yandex internal --><td>
      <a href="https://habr.com/ru/company/yandex/blog/209324/">Cocaine</a><br/>
      <a href="https://cloud.yandex.ru/">Yandex.Cloud</a>
    </td>
    <!-- Analogs --><td>
      <a href="https://github.com/cocaine/cocaine-core">Cocaine</a> (Open source by Yandex)<br/>
      <a href="https://www.openshift.com/">OpenShift</a> (Open source by RedHat)<br/>
      <a href="https://cloud.yandex.ru/">Yandex.Cloud</a> (Commercial by Yandex)<br/>
      <a href="https://aws.amazon.com/">AWS</a> (Commercial by Amazon)<br/>
      <a href="https://azure.microsoft.com/">Azure</a> (Commercial by Microsoft)
    </td>
  </tr>
  <tr>
    <!-- Technology --><td>Nginx configuration tool</td>
    <!-- Yandex internal --><td>
      <a href="https://habr.com/ru/company/yandex/blog/327590/">Gixy</a>
    </td>
    <!-- Analogs --><td>
      <a href="https://github.com/yandex/gixy/">Gixy</a> (Open source by Yandex)
    </td>
  </tr>
  <tr>
    <!-- Technology --><td>L7 load balancer</td>
    <!-- Yandex internal --><td>
      <a href="https://github.com/yandex/balancer">Balancer</a> (Archived)
    </td>
    <!-- Analogs --><td>
      <a href="https://github.com/envoyproxy/envoy">Envoy</a>
    </td>
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
    <!-- Technology --><td>Machine learning framework</td>
    <!-- Yandex internal --><td>
      <a href="https://habr.com/ru/company/yandex/blog/174213/">FML</a><br/>
      <a href="https://yandex.ru/company/technologies/matrixnet/">MatrixNet</a>
    <!-- Analogs --><td>
      <a href="https://github.com/google/caliban">Caliban</a> (Open source by Google)
    </td>
  </tr>
  <tr>
    <!-- Technology --><td>Simple tasks outsoursing</td>
    <!-- Yandex internal --><td><a href="https://habr.com/ru/company/yandex/blog/305956/">Toloka</a>
    <!-- Analogs --><td>
      <a href="https://toloka.yandex.ru/">Toloka</a> (Commercial by Yandex)<br/>
      <a href="https://www.mturk.com/">Amazon Mechanical turk</a> (Commercial by Amazon)
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
      <a href="https://yandex.ru/tracker/">Tracker</a> (Commercial by Yandex)<br/>
      <a href="https://www.atlassian.com/software/jira">Jira</a> (Commercial by Atlassian)
    </td>
  </tr>
  <tr>
    <!-- Technology --><td>Wiki engine</td>
    <!-- Yandex internal --><td><a href="https://connect.yandex.ru/?noredirect=">Wiki</a></td>
    <!-- Analogs --><td>
      <a href="https://connect.yandex.ru/?noredirect=">Wiki</a> (Commercial by Yandex)<br/>
      <a href="https://www.mediawiki.org/">Mediawiki</a> (Open source)<br/>
      <a href="https://www.atlassian.com/software/confluence">Confluence</a> (Commercial by Atlassian)
    </td>
  </tr>
</table>


## Contibuting

Feel free to add any technologies.
If you add internal Yandex technology, you must provide link that prooves this technology is not under NDA.
Usually this is link to [official Yandex blog on habr.com](https://habr.com/ru/company/yandex/), link to [official Yandex technologies catalog](https://yandex.ru/dev) or link to [official Yandex GitHub repository](https://github.com/yandex).


## Why HTML in .md?

Big markdown tables are messy. Big html tables are just a little less messy, so I choosed html.
