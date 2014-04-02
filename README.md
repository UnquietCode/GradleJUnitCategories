```
BenBoxMachine:GradleCategories ben$ gradle clean test --info --stacktrace
Starting Build
Settings evaluated using empty settings script.
Projects loaded. Root project using build file '/Users/ben/Documents/GradleCategories/build.gradle'.
Included projects: [root project 'GradleCategories']
Evaluating root project 'GradleCategories' using build file '/Users/ben/Documents/GradleCategories/build.gradle'.
Compiling build file '/Users/ben/Documents/GradleCategories/build.gradle' using StatementExtractingScriptTransformer.
Compiling build file '/Users/ben/Documents/GradleCategories/build.gradle' using BuildScriptTransformer.
All projects evaluated.
Selected primary tasks 'clean', 'test'
Tasks to be executed: [task ':clean', task ':compileJava', task ':compileGroovy', task ':processResources', task ':classes', task ':compileTestJava', task ':compileTestGroovy', task ':processTestResources', task ':testClasses', task ':test']
:clean (Thread[main,5,main]) started.
:clean
Executing task ':clean' (up-to-date check took 0.001 secs) due to:
  Task has not declared any outputs.
:clean (Thread[main,5,main]) completed. Took 0.007 secs.
:compileJava (Thread[main,5,main]) started.
:compileJava
Skipping task ':compileJava' as it has no source files.
:compileJava UP-TO-DATE
:compileJava (Thread[main,5,main]) completed. Took 0.002 secs.
:compileGroovy (Thread[main,5,main]) started.
:compileGroovy
Skipping task ':compileGroovy' as it has no source files.
:compileGroovy UP-TO-DATE
:compileGroovy (Thread[main,5,main]) completed. Took 0.022 secs.
:processResources (Thread[main,5,main]) started.
:processResources
Executing task ':processResources' (up-to-date check took 0.062 secs) due to:
  Output file /Users/ben/Documents/GradleCategories/build/resources/main has changed.
  Output file /Users/ben/Documents/GradleCategories/build/resources/main/B.txt has been removed.
:processResources (Thread[main,5,main]) completed. Took 0.158 secs.
:classes (Thread[main,5,main]) started.
:classes
Skipping task ':classes' as it has no actions.
:classes (Thread[main,5,main]) completed. Took 0.001 secs.
:compileTestJava (Thread[main,5,main]) started.
:compileTestJava
Skipping task ':compileTestJava' as it has no source files.
:compileTestJava UP-TO-DATE
:compileTestJava (Thread[main,5,main]) completed. Took 0.002 secs.
:compileTestGroovy (Thread[main,5,main]) started.
:compileTestGroovy
Executing task ':compileTestGroovy' (up-to-date check took 0.44 secs) due to:
  Output file /Users/ben/Documents/GradleCategories/build/classes/test has changed.
  Output file /Users/ben/Documents/GradleCategories/build/classes/test/com/test/SomeTest.class has been removed.
  Output file /Users/ben/Documents/GradleCategories/build/classes/test/com/test/TestCategory.class has been removed.
Starting process 'Gradle Worker 1'. Working directory: /Users/ben/Documents/GradleCategories Command: /Library/Java/JavaVirtualMachines/jdk1.7.0_45.jdk/Contents/Home/bin/java -Dfile.encoding=UTF-8 -cp /Applications/dev/gradle-1.11/lib/gradle-base-services-1.11.jar:/Applications/dev/gradle-1.11/lib/gradle-core-1.11.jar:/Applications/dev/gradle-1.11/lib/gradle-cli-1.11.jar:/Applications/dev/gradle-1.11/lib/gradle-native-1.11.jar:/Applications/dev/gradle-1.11/lib/gradle-messaging-1.11.jar:/Applications/dev/gradle-1.11/lib/slf4j-api-1.7.5.jar:/Applications/dev/gradle-1.11/lib/logback-classic-1.0.13.jar:/Applications/dev/gradle-1.11/lib/logback-core-1.0.13.jar:/Applications/dev/gradle-1.11/lib/jul-to-slf4j-1.7.5.jar:/Applications/dev/gradle-1.11/lib/guava-jdk5-14.0.1.jar org.gradle.process.internal.launcher.GradleWorkerMain
Successfully started process 'Gradle Worker 1'
Started Gradle compiler daemon (0.648 secs) with fork options DaemonForkOptions{minHeapSize=null, maxHeapSize=null, jvmArgs=[], classpath=[/Users/ben/.gradle/caches/modules-2/files-2.1/org.codehaus.groovy/groovy-all/2.2.2/b9bf4b39c09afb24d043e15c50044986a4436edd/groovy-all-2.2.2-indy.jar, /Applications/dev/gradle-1.11/lib/ant-1.9.2.jar, /Applications/dev/gradle-1.11/lib/ant-launcher-1.9.2.jar]}.
Executing org.gradle.api.internal.tasks.compile.ApiGroovyCompiler@1b80fd99 in compiler daemon.
Compiling with JDK Java compiler API.
Successfully executed org.gradle.api.internal.tasks.compile.ApiGroovyCompiler@1b80fd99 in compiler daemon.
:compileTestGroovy (Thread[main,5,main]) completed. Took 1.989 secs.
:processTestResources (Thread[main,5,main]) started.
:processTestResources
Executing task ':processTestResources' (up-to-date check took 0.007 secs) due to:
  Output file /Users/ben/Documents/GradleCategories/build/resources/test has changed.
  Output file /Users/ben/Documents/GradleCategories/build/resources/test/C.txt has been removed.
:processTestResources (Thread[main,5,main]) completed. Took 0.026 secs.
:testClasses (Thread[main,5,main]) started.
:testClasses
Skipping task ':testClasses' as it has no actions.
:testClasses (Thread[main,5,main]) completed. Took 0.002 secs.
:test (Thread[main,5,main]) started.
:test
Executing task ':test' (up-to-date check took 0.043 secs) due to:
  Output file /Users/ben/Documents/GradleCategories/build/reports/tests has changed.
  Output file /Users/ben/Documents/GradleCategories/build/test-results/binary/test has changed.
  Output file /Users/ben/Documents/GradleCategories/build/test-results has changed.
Starting process 'Gradle Worker 2'. Working directory: /Users/ben/Documents/GradleCategories Command: /Library/Java/JavaVirtualMachines/jdk1.7.0_45.jdk/Contents/Home/bin/java -Djava.security.manager=jarjar.org.gradle.process.internal.child.BootstrapSecurityManager -Dfile.encoding=UTF-8 -ea -cp /Users/ben/.gradle/caches/1.11/workerMain/gradle-worker.jar jarjar.org.gradle.process.internal.launcher.GradleWorkerMain
Successfully started process 'Gradle Worker 2'
Gradle Worker 2 executing tests.
Gradle Worker 2 finished executing tests.

com.test.SomeTest > initializationError FAILED
    org.gradle.api.InvalidUserDataException: Can't load category class [com.test.TestCategory.CategoryA].

        Caused by:
        java.lang.ClassNotFoundException: com.test.TestCategory.CategoryA

1 test completed, 1 failed
Finished generating test XML results (0.028 secs)
Generating HTML test report...
Finished generating test html results (0.028 secs)
:test FAILED
:test (Thread[main,5,main]) completed. Took 1.056 secs.

FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':test'.
> There were failing tests. See the report at: file:///Users/ben/Documents/GradleCategories/build/reports/tests/index.html

* Try:
Run with --debug option to get more log output.

* Exception is:
org.gradle.api.tasks.TaskExecutionException: Execution failed for task ':test'.
	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.executeActions(ExecuteActionsTaskExecuter.java:69)
	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.execute(ExecuteActionsTaskExecuter.java:46)
	at org.gradle.api.internal.tasks.execution.PostExecutionAnalysisTaskExecuter.execute(PostExecutionAnalysisTaskExecuter.java:35)
	at org.gradle.api.internal.tasks.execution.SkipUpToDateTaskExecuter.execute(SkipUpToDateTaskExecuter.java:64)
	at org.gradle.api.internal.tasks.execution.ValidatingTaskExecuter.execute(ValidatingTaskExecuter.java:58)
	at org.gradle.api.internal.tasks.execution.SkipEmptySourceFilesTaskExecuter.execute(SkipEmptySourceFilesTaskExecuter.java:42)
	at org.gradle.api.internal.tasks.execution.SkipTaskWithNoActionsExecuter.execute(SkipTaskWithNoActionsExecuter.java:52)
	at org.gradle.api.internal.tasks.execution.SkipOnlyIfTaskExecuter.execute(SkipOnlyIfTaskExecuter.java:53)
	at org.gradle.api.internal.tasks.execution.ExecuteAtMostOnceTaskExecuter.execute(ExecuteAtMostOnceTaskExecuter.java:43)
	at org.gradle.api.internal.AbstractTask.executeWithoutThrowingTaskFailure(AbstractTask.java:289)
	at org.gradle.execution.taskgraph.AbstractTaskPlanExecutor$TaskExecutorWorker.executeTask(AbstractTaskPlanExecutor.java:79)
	at org.gradle.execution.taskgraph.AbstractTaskPlanExecutor$TaskExecutorWorker.processTask(AbstractTaskPlanExecutor.java:63)
	at org.gradle.execution.taskgraph.AbstractTaskPlanExecutor$TaskExecutorWorker.run(AbstractTaskPlanExecutor.java:51)
	at org.gradle.execution.taskgraph.DefaultTaskPlanExecutor.process(DefaultTaskPlanExecutor.java:23)
	at org.gradle.execution.taskgraph.DefaultTaskGraphExecuter.execute(DefaultTaskGraphExecuter.java:86)
	at org.gradle.execution.SelectedTaskExecutionAction.execute(SelectedTaskExecutionAction.java:29)
	at org.gradle.execution.DefaultBuildExecuter.execute(DefaultBuildExecuter.java:61)
	at org.gradle.execution.DefaultBuildExecuter.access$200(DefaultBuildExecuter.java:23)
	at org.gradle.execution.DefaultBuildExecuter$2.proceed(DefaultBuildExecuter.java:67)
	at org.gradle.execution.DryRunBuildExecutionAction.execute(DryRunBuildExecutionAction.java:32)
	at org.gradle.execution.DefaultBuildExecuter.execute(DefaultBuildExecuter.java:61)
	at org.gradle.execution.DefaultBuildExecuter.execute(DefaultBuildExecuter.java:54)
	at org.gradle.initialization.DefaultGradleLauncher.doBuildStages(DefaultGradleLauncher.java:166)
	at org.gradle.initialization.DefaultGradleLauncher.doBuild(DefaultGradleLauncher.java:113)
	at org.gradle.initialization.DefaultGradleLauncher.run(DefaultGradleLauncher.java:81)
	at org.gradle.launcher.exec.InProcessBuildActionExecuter$DefaultBuildController.run(InProcessBuildActionExecuter.java:64)
	at org.gradle.launcher.cli.ExecuteBuildAction.run(ExecuteBuildAction.java:33)
	at org.gradle.launcher.cli.ExecuteBuildAction.run(ExecuteBuildAction.java:24)
	at org.gradle.launcher.exec.InProcessBuildActionExecuter.execute(InProcessBuildActionExecuter.java:35)
	at org.gradle.launcher.exec.InProcessBuildActionExecuter.execute(InProcessBuildActionExecuter.java:26)
	at org.gradle.launcher.cli.RunBuildAction.run(RunBuildAction.java:50)
	at org.gradle.internal.Actions$RunnableActionAdapter.execute(Actions.java:171)
	at org.gradle.launcher.cli.CommandLineActionFactory$ParseAndBuildAction.execute(CommandLineActionFactory.java:201)
	at org.gradle.launcher.cli.CommandLineActionFactory$ParseAndBuildAction.execute(CommandLineActionFactory.java:174)
	at org.gradle.launcher.cli.CommandLineActionFactory$WithLogging.execute(CommandLineActionFactory.java:170)
	at org.gradle.launcher.cli.CommandLineActionFactory$WithLogging.execute(CommandLineActionFactory.java:139)
	at org.gradle.launcher.cli.ExceptionReportingAction.execute(ExceptionReportingAction.java:33)
	at org.gradle.launcher.cli.ExceptionReportingAction.execute(ExceptionReportingAction.java:22)
	at org.gradle.launcher.Main.doAction(Main.java:46)
	at org.gradle.launcher.bootstrap.EntryPoint.run(EntryPoint.java:45)
	at org.gradle.launcher.Main.main(Main.java:37)
	at org.gradle.launcher.bootstrap.ProcessBootstrap.runNoExit(ProcessBootstrap.java:50)
	at org.gradle.launcher.bootstrap.ProcessBootstrap.run(ProcessBootstrap.java:32)
	at org.gradle.launcher.GradleMain.main(GradleMain.java:23)
Caused by: org.gradle.api.GradleException: There were failing tests. See the report at: file:///Users/ben/Documents/GradleCategories/build/reports/tests/index.html
	at org.gradle.api.tasks.testing.Test.handleTestFailures(Test.java:1173)
	at org.gradle.api.tasks.testing.Test.executeTests(Test.java:507)
	at org.gradle.internal.reflect.JavaMethod.invoke(JavaMethod.java:63)
	at org.gradle.api.internal.project.taskfactory.AnnotationProcessingTaskFactory$StandardTaskAction.doExecute(AnnotationProcessingTaskFactory.java:219)
	at org.gradle.api.internal.project.taskfactory.AnnotationProcessingTaskFactory$StandardTaskAction.execute(AnnotationProcessingTaskFactory.java:212)
	at org.gradle.api.internal.project.taskfactory.AnnotationProcessingTaskFactory$StandardTaskAction.execute(AnnotationProcessingTaskFactory.java:201)
	at org.gradle.api.internal.AbstractTask$TaskActionWrapper.execute(AbstractTask.java:533)
	at org.gradle.api.internal.AbstractTask$TaskActionWrapper.execute(AbstractTask.java:516)
	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.executeAction(ExecuteActionsTaskExecuter.java:80)
	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.executeActions(ExecuteActionsTaskExecuter.java:61)
	... 43 more


BUILD FAILED
```
