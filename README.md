# ContributionsToOpenSource

## ganglia-web

- [Issue#318](https://github.com/ganglia/ganglia-web/issues/318) incorrect alt value in meta_view, [Pull request](https://github.com/ganglia/ganglia-web/pull/319) (accepted)

## hadoop

- [HADOOP-10738](https://issues.apache.org/jira/browse/HADOOP-10738) Dynamically adjust distcp configuration by adding distcp-site.xml into code base (in progress)
- [HADOOP-13773](https://issues.apache.org/jira/browse/HADOOP-13773) wrong jvm args in hadoop-env (accepted)
- [HADOOP-13865](https://issues.apache.org/jira/browse/HADOOP-13865) add tools to classpath by default in branch-2 (reject)
- [HADOOP-13869](https://issues.apache.org/jira/browse/HADOOP-13869) using HADOOP_USER_CLASSPATH_FIRST inconsistently (in progress)
- [HADOOP-13898](https://issues.apache.org/jira/browse/HADOOP-13898) should set HADOOP_JOB_HISTORYSERVER_HEAPSIZE only if it's empty on branch2 (accepted)
- [HADOOP-14065](https://issues.apache.org/jira/browse/HADOOP-14065) AliyunOSS: oss directory filestatus should use meta time (accepted)
- [HADOOP-14069](https://issues.apache.org/jira/browse/HADOOP-14069) AliyunOSS: listStatus returns wrong file info (accepted)
- [HADOOP-14176](https://issues.apache.org/jira/browse/HADOOP-14176) distcp reports beyond physical memory limits on 2.X (in progress)
- [HADOOP-14189](https://issues.apache.org/jira/browse/HADOOP-14189) add distcp-site.xml for distcp on branch-2 (duplicate)
- [HADOOP-15633](https://issues.apache.org/jira/browse/HADOOP-15633) fs.TrashPolicyDefault: Can't create trash directory (accepted)
- [HADOOP-16814](https://issues.apache.org/jira/browse/HADOOP-16814) Add dropped connections metric for Server (in progress)
- [MAPREDUCE-7174](https://issues.apache.org/jira/browse/MAPREDUCE-7174) MapReduce example wordmedian should handle generic options (accepted)
- [HDFS-12999](https://issues.apache.org/jira/browse/HDFS-12999) When reach the end of the block group, it may not need to flush all the data packets(flushAllInternals) twice (accepted)
- [HDFS-13821](https://issues.apache.org/jira/browse/HDFS-13821) RBF: Add dfs.federation.router.mount-table.cache.enable so that users can disable cache (accepted)
- [HDFS-13863](https://issues.apache.org/jira/browse/HDFS-13863) FsDatasetImpl should log DiskOutOfSpaceException (accepted)
- [HDFS-13293](https://issues.apache.org/jira/browse/HDFS-13293) RBF: The RouterRPCServer should transfer CallerContext and client ip to NamenodeRpcServer (in progress)
- [HDFS-13248](https://issues.apache.org/jira/browse/HDFS-13248) RBF: Namenode need to choose block location for the client (in progress)
- [HDFS-13802](https://issues.apache.org/jira/browse/HDFS-13802) RBF: Remove FSCK from Router Web UI (accepted)
- [HDFS-14114](https://issues.apache.org/jira/browse/HDFS-14114) RBF: MIN_ACTIVE_RATIO should be configurable (accepted)
- [HDFS-14161](https://issues.apache.org/jira/browse/HDFS-14161) RBF: Throw StandbyException instead of IOException so that client can retry when can not get connection (accepted)
- [HDFS-14207](https://issues.apache.org/jira/browse/HDFS-14207) ZKFC should catch exception when ha configuration missing (accepted)
- [HDFS-14230](https://issues.apache.org/jira/browse/HDFS-14230) RBF: Throw RetriableException instead of IOException when no namenodes available (accepted)
- [HDFS-13596](https://issues.apache.org/jira/browse/HDFS-13596) RNN restart fails after RollingUpgrade from 2.x to 3.x (accepted)
- [HDFS-14396](https://issues.apache.org/jira/browse/HDFS-14396) Failed to load image from FSImageFile when downgrade from 3.x to 2.x (accepted)
- [HDFS-14796](https://issues.apache.org/jira/browse/HDFS-14796) Define LOG instead of BlockManager.LOG in ErasureCodingWork (accepted)
- [HDFS-14802](https://issues.apache.org/jira/browse/HDFS-14802) The feature of protect directories should be used in RenameOp（accepted）
- [HDFS-14831](https://issues.apache.org/jira/browse/HDFS-14831) Downgrade Failed from 3.2.0 to 2.7 because of incompatible stringtable（in progress）
- [HDFS-14847](https://issues.apache.org/jira/browse/HDFS-14847) Erasure Coding: Blocks are over-replicated while EC decommissioning （accepted）
- [HDFS-14852](https://issues.apache.org/jira/browse/HDFS-14852) Remove of LowRedundancyBlocks do NOT remove the block from all queues (in progress)
- [HDFS-14873](https://issues.apache.org/jira/browse/HDFS-14873) Fix dfsadmin doc for triggerBlockReport (accepted)
- [HDFS-14918](https://issues.apache.org/jira/browse/HDFS-14918) Remove useless getRedundancyThread from BlockManagerTestUtil (accepted)
- [HDFS-14920](https://issues.apache.org/jira/browse/HDFS-14920) Erasure Coding: Decommission may hang If one or more datanodes are out of service during decommission (accepted)
- [HDFS-14923](https://issues.apache.org/jira/browse/HDFS-14923) Remove dead code from HealthMonitor (accepted)
- [HDFS-14946](https://issues.apache.org/jira/browse/HDFS-14946) Erasure Coding: Block recovery failed during decommissioning (accepted)
- [HDFS-14975](https://issues.apache.org/jira/browse/HDFS-14975) Add LF for SetECPolicyCommand usage (accepted)
- [HDFS-14998](https://issues.apache.org/jira/browse/HDFS-14998) [SBN read] Update Observer Namenode doc for ZKFC after HDFS-14130 (accepted)
- [HDFS-15023](https://issues.apache.org/jira/browse/HDFS-15023) [SBN read] ZKFC should check the state before joining the election (accepted)
- [HDFS-15062](https://issues.apache.org/jira/browse/HDFS-15062) Add LOG when sendIBRs failed (accepted)
- [HDFS-15078](https://issues.apache.org/jira/browse/HDFS-15078) RBF: Should check connection channel before sending rpc to namenode (in progress)
- [HDFS-15079](https://issues.apache.org/jira/browse/HDFS-15079) RBF: Client maybe get an unexpected result with network anomaly (in progress)
- [HDFS-15081](https://issues.apache.org/jira/browse/HDFS-15081) Typo in RetryCache#waitForCompletion annotation (accepted)
- [HDFS-15092](https://issues.apache.org/jira/browse/HDFS-15092) TestRedudantBlocks#testProcessOverReplicatedAndRedudantBlock sometimes fails (accepted)
- [HDFS-15514](https://issues.apache.org/jira/browse/HDFS-15514) Remove useless dfs.webhdfs.enabled (accepted)



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
- [HIVE-16943](https://issues.apache.org/jira/browse/HIVE-16943) MoveTask should separate src FileSystem from dest FileSystem (accepted)

## zeppelin
- [ZEPPELIN-295](https://issues.apache.org/jira/browse/ZEPPELIN-295) Property "spark.executor.memory" doesn't have effect (in progress)

## tez
- [TEZ-3565](https://issues.apache.org/jira/browse/TEZ-3565) amConfig should check queuename isEmpty (accepted)
- [TEZ-3616](https://issues.apache.org/jira/browse/TEZ-3616) TestMergeManager#testLocalDiskMergeMultipleTasks fails intermittently (accepted)
- [TEZ-3649](https://issues.apache.org/jira/browse/TEZ-3649) AsyncHttpConnection should add StopWatch start (accepted)
