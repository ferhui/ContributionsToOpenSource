# ContributionsToOpenSource

## ganglia-web

- [Issue#318](https://github.com/ganglia/ganglia-web/issues/318) incorrect alt value in meta_view, [Pull request](https://github.com/ganglia/ganglia-web/pull/319) (accepted)

## hadoop-common

- [HADOOP-10738](https://issues.apache.org/jira/browse/HADOOP-10738) Dynamically adjust distcp configuration by adding distcp-site.xml into code base (in progress)
- [HADOOP-13773](https://issues.apache.org/jira/browse/HADOOP-13773) wrong jvm args in hadoop-env (accepted)
- [HADOOP-13865](https://issues.apache.org/jira/browse/HADOOP-13865) add tools to classpath by default in branch-2 (reject)
- [HADOOP-13869](https://issues.apache.org/jira/browse/HADOOP-13869) using HADOOP_USER_CLASSPATH_FIRST inconsistently (in progress)
- [HADOOP-13898](https://issues.apache.org/jira/browse/HADOOP-13898) should set HADOOP_JOB_HISTORYSERVER_HEAPSIZE only if it's empty on branch2 (accepted)
- [HADOOP-14065](https://issues.apache.org/jira/browse/HADOOP-14065) AliyunOSS: oss directory filestatus should use meta time (accepted)
- [HADOOP-14069](https://issues.apache.org/jira/browse/HADOOP-14069) AliyunOSS: listStatus returns wrong file info (accepted)
- [HADOOP-14176](https://issues.apache.org/jira/browse/HADOOP-14176) distcp reports beyond physical memory limits on 2.X (in progress)
- [HADOOP-14189](https://issues.apache.org/jira/browse/HADOOP-14189) add distcp-site.xml for distcp on branch-2 (duplicate)

## hive

- [HIVE-14804](https://issues.apache.org/jira/browse/HIVE-14804) hplsql multi connection can not switch back to hive (accepted)
- [HIVE-15096](https://issues.apache.org/jira/browse/HIVE-15096) hplsql registerUDF error (accepted)
- [HIVE-15221](https://issues.apache.org/jira/browse/HIVE-15221) improvment for MapJoin checkMemoryStatus (in progress)
- [HIVE-15257](https://issues.apache.org/jira/browse/HIVE-15257) remove useless cleanupReaders in OrcEncodedDataReader (accepted)
- [HIVE-15285](https://issues.apache.org/jira/browse/HIVE-15285) err info for itests mvn building is not correct (reject)
- [HIVE-15314](https://issues.apache.org/jira/browse/HIVE-15314) ThriftCLIService should LOG.error rather than LOG.warn when Exception occurs (reject)
- [HIVE-15378](https://issues.apache.org/jira/browse/HIVE-15378) clean up HADOOP_USER_CLASSPATH_FIRST in bin scripts (accepted)
- [HIVE-15407](https://issues.apache.org/jira/browse/HIVE-15407) add distcp to classpath by default, because hive depends on it. (accepted)
- [HIVE-15444](https://issues.apache.org/jira/browse/HIVE-15444) tez.queue.name is invalid after tez job running on CLI (in progress)
- [HIVE-15849](https://issues.apache.org/jira/browse/HIVE-15849) hplsql should add enterGlobalScope func to UDF (accepted)
- [HIVE-15855](https://issues.apache.org/jira/browse/HIVE-15855) throws NPE when using Hplsql UDF (accepted)
- [HIVE-16043](https://issues.apache.org/jira/browse/HIVE-16043) TezConfiguration.TEZ_QUEUE_NAME instead of tez.queue.name (accepted)
- [HIVE-16187](https://issues.apache.org/jira/browse/HIVE-16187) Flaky Tests:TestHostAffinitySplitLocationProvider#testConsistentHashingFallback usually timed out (accepted)
- [HIVE-16239](https://issues.apache.org/jira/browse/HIVE-16239) remove useless hiveserver (accepted)
- [HIVE-16920](https://issues.apache.org/jira/browse/HIVE-16920) remove useless uri.getScheme() from EximUtil (accepted)
- [HIVE-16939](https://issues.apache.org/jira/browse/HIVE-16939) metastore error: 'export: -Dproc_metastore : not a valid identifier' (accepted)
- [HIVE-16943](https://issues.apache.org/jira/browse/HIVE-16943) MoveTask should separate src FileSystem from dest FileSystem (in progress)

## zeppelin
- [ZEPPELIN-295](https://issues.apache.org/jira/browse/ZEPPELIN-295) Property "spark.executor.memory" doesn't have effect (in progress)

## tez
- [TEZ-3565](https://issues.apache.org/jira/browse/TEZ-3565) amConfig should check queuename isEmpty (accepted)
- [TEZ-3616](https://issues.apache.org/jira/browse/TEZ-3616) TestMergeManager#testLocalDiskMergeMultipleTasks fails intermittently (accepted)
- [TEZ-3649](https://issues.apache.org/jira/browse/TEZ-3649) AsyncHttpConnection should add StopWatch start (accepted)
