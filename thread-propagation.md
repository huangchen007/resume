```
[2020-09-15 02:20:08] [ERROR] - ReplayReporter - report error
java.lang.ClassCastException: com.alibaba.mtc.MtContextRunnable cannot be cast to com.jd.tp.jcase.recording.agent.reporter.impl.ReplayReporter$ReportRunner
at com.jd.tp.jcase.recording.agent.reporter.impl.ReplayReporter$1.rejectedExecution(ReplayReporter.java:106)
at java.util.concurrent.ThreadPoolExecutor.reject(ThreadPoolExecutor.java:767)
at java.util.concurrent.ThreadPoolExecutor.execute(ThreadPoolExecutor.java:658)
at com.jd.tp.jcase.recording.agent.reporter.impl.ReplayReporter.doReport(ReplayReporter.java:118)
at com.jd.tp.jcase.recording.agent.reporter.AbstractReporter.report(AbstractReporter.java:72)
at com.jd.tp.jcase.recording.agent.reporter.AbstractReporter$ReporterThread.doRun(AbstractReporter.java:112)
at com.jd.tp.jcase.recording.agent.reporter.AbstractReporter$ReporterThread.run(AbstractReporter.java:87)
```
