# TruthJetifier

$ gradlew clean test
> Task :app:compileDebugUnitTestKotlin FAILED

FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':app:compileDebugUnitTestKotlin'.
> Could not resolve all artifacts for configuration ':app:debugUnitTestCompileClasspath'.
   > Failed to transform artifact 'truth-android-support-v4.jar (com.pkware.truth-android:truth-android-support-v4:1.1.0)' to match attributes {artifactType=android-classes, org.gradle.usage=java-runtime-jars}
      > Execution failed for JetifyTransform: /.gradle/caches/modules-2/files-2.1/com.pkware.truth-android/truth-android-support-v4/1.1.0/c53b5ed405f269573ecbd758c42ca26bbc2d3d82/truth-android-support-v4-1.1.0.jar.
         > Failed to transform '/.gradle/caches/modules-2/files-2.1/com.pkware.truth-android/truth-android-support-v4/1.1.0/c53b5ed405f269573ecbd758c42ca26bbc2d3d82/truth-android-support-v4-1.1.0.jar' using Jetifier. Reason: duplicate entry: androidx/core/R.class. (Run with --stacktrace for more details.)

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output. Run with --scan to get full insights.

* Get more help at https://help.gradle.org

Deprecated Gradle features were used in this build, making it incompatible with Gradle 6.0.
Use '--warning-mode all' to show the individual deprecation warnings.
See https://docs.gradle.org/5.1.1/userguide/command_line_interface.html#sec:command_line_warnings

BUILD FAILED in 3s
16 actionable tasks: 15 executed, 1 up-to-date
