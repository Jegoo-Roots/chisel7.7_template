error id: file://<WORKSPACE>/build.sbt:
file://<WORKSPACE>/build.sbt
empty definition using pc, found symbol in pc: 
empty definition using semanticdb
empty definition using fallback
non-local guesses:

offset: 746
uri: file://<WORKSPACE>/build.sbt
text:
```scala
// See README.md for license details.

ThisBuild / scalaVersion     := "2.13.18"
ThisBuild / version          := "0.1.0"
ThisBuild / organization     := "%ORGANIZATION%"

val chiselVersion = "7.7.0"

lazy val root = (project in file("."))
  .settings(
    name := "%NAME%",
    libraryDependencies ++= Seq(
      "org.chipsalliance" %% "chisel" % chiselVersion,
      "org.scalatest" %% "scalatest" % "3.2.19" % "test",
    ),
    scalacOptions ++= Seq(
      "-language:reflectiveCalls",
      "-deprecation",
      "-feature",
      "-Xcheckinit",
      "-Ymacro-annotations",
    ),
    addCompilerPlugin("org.chipsalliance" % "chisel-plugin" % chiselVersion cross CrossVersion.full),
  )
/usr/lib/jvm/java-1.17.0-openjdk-amd64/bin/java -Djlin@@e.terminal=jline.UnsupportedTerminal -Dsbt.log.noformat=true -Dfile.encoding=UTF-8 -Dgrouping.with.qualified.names.enabled=true -Dseparate.prod.test.sources.enabled=true -Djava.io.tmpdir=<HOME>/tmp -Didea.managed=true -Dfile.encoding=UTF-8 -Didea.installation.dir=<HOME>/software/idea-IC-252.26830.84 -jar <HOME>/.local/share/JetBrains/IdeaIC2025.2/Scala/launcher/sbt-launch.jar
  [info] welcome to sbt 1.12.4 (Private Build Java 17.0.10)
[info] loading global plugins from <HOME>/.sbt/1.0/plugins
  [info] loading settings for project chisel7_template-build from plugins.sbt...
[info] loading project definition from <WORKSPACE>/project
  [info] loading settings for project root from build.sbt...
[info] set current project to %NAME% (in build file:<WORKSPACE>/)
  [info] sbt server started at local://<HOME>/.sbt/1.0/server/41e66aec47d908ef1946/sock
[info] started sbt server
sbt:0AME
[info] Defining Global / generateManagedSourcesDuringStructureDump, Global / sbtStructureOptions and 2 others.
[info] The new values will be used by cleanKeepGlobs
  [info] 	Run `last` for details.
  [info] Reapplying settings...
[info] set current project to %NAME% (in build file:<WORKSPACE>/)
  [info] Applying State transformations org.jetbrains.sbt.CreateTasks, sbt.jetbrains.LogDownloadArtifacts from <HOME>/.local/share/JetBrains/IdeaIC2025.2/Scala/repo/org/jetbrains/scala/sbt-structure-extractor_2.12_1.3/2025.3.1/sbt-structure-extractor_2.12_1.3-2025.3.1.jar
  [info] Reapplying settings...
[info] set current project to %NAME% (in build file:<WORKSPACE>/)
  [info] Reapplying settings...
[info] set current project to %NAME% (in build file:<WORKSPACE>/)
  [info] downloading https://repo1.maven.org/maven2/org/scala-lang/scala2-sbt-bridge/2.13.18/scala2-sbt-bridge-2.13.18.pom
[info] downloaded https://repo1.maven.org/maven2/org/scala-lang/scala2-sbt-bridge/2.13.18/scala2-sbt-bridge-2.13.18.pom
[info] downloading https://repo1.maven.org/maven2/org/chipsalliance/chisel_2.13/7.7.0/chisel_2.13-7.7.0.pom
[info] downloaded https://repo1.maven.org/maven2/org/chipsalliance/chisel_2.13/7.7.0/chisel_2.13-7.7.0.pom
[info] downloading https://repo1.maven.org/maven2/org/apache/commons/commons-text/1.15.0/commons-text-1.15.0.pom
[info] downloading https://repo1.maven.org/maven2/io/github/json4s/json4s-native_2.13/4.1.0/json4s-native_2.13-4.1.0.pom
[info] downloaded https://repo1.maven.org/maven2/org/apache/commons/commons-text/1.15.0/commons-text-1.15.0.pom
[info] downloaded https://repo1.maven.org/maven2/io/github/json4s/json4s-native_2.13/4.1.0/json4s-native_2.13-4.1.0.pom
[info] downloading https://repo1.maven.org/maven2/org/apache/commons/commons-parent/93/commons-parent-93.pom
[info] downloaded https://repo1.maven.org/maven2/org/apache/commons/commons-parent/93/commons-parent-93.pom
[info] downloading https://repo1.maven.org/maven2/io/github/json4s/json4s-native-core_2.13/4.1.0/json4s-native-core_2.13-4.1.0.pom
[info] downloading https://repo1.maven.org/maven2/io/github/json4s/json4s-core_2.13/4.1.0/json4s-core_2.13-4.1.0.pom
[info] downloaded https://repo1.maven.org/maven2/io/github/json4s/json4s-core_2.13/4.1.0/json4s-core_2.13-4.1.0.pom
[info] downloaded https://repo1.maven.org/maven2/io/github/json4s/json4s-native-core_2.13/4.1.0/json4s-native-core_2.13-4.1.0.pom
[info] downloading https://repo1.maven.org/maven2/io/github/json4s/json4s-scalap_2.13/4.1.0/json4s-scalap_2.13-4.1.0.pom
[info] downloading https://repo1.maven.org/maven2/io/github/json4s/json4s-ast_2.13/4.1.0/json4s-ast_2.13-4.1.0.pom
[info] downloaded https://repo1.maven.org/maven2/io/github/json4s/json4s-ast_2.13/4.1.0/json4s-ast_2.13-4.1.0.pom
[info] downloaded https://repo1.maven.org/maven2/io/github/json4s/json4s-scalap_2.13/4.1.0/json4s-scalap_2.13-4.1.0.pom
[info] downloading https://repo1.maven.org/maven2/org/chipsalliance/chisel-plugin_2.13.18/7.7.0/chisel-plugin_2.13.18-7.7.0.pom
[info] downloaded https://repo1.maven.org/maven2/org/chipsalliance/chisel-plugin_2.13.18/7.7.0/chisel-plugin_2.13.18-7.7.0.pom
[info] downloading https://repo1.maven.org/maven2/org/scala-lang/scala2-sbt-bridge/2.13.18/scala2-sbt-bridge-2.13.18.jar
[info] downloaded https://repo1.maven.org/maven2/org/scala-lang/scala2-sbt-bridge/2.13.18/scala2-sbt-bridge-2.13.18.jar
[info] downloading https://repo1.maven.org/maven2/io/github/json4s/json4s-ast_2.13/4.1.0/json4s-ast_2.13-4.1.0.jar
[info] downloading https://repo1.maven.org/maven2/io/github/json4s/json4s-native_2.13/4.1.0/json4s-native_2.13-4.1.0.jar
[info] downloading https://repo1.maven.org/maven2/io/github/json4s/json4s-native-core_2.13/4.1.0/json4s-native-core_2.13-4.1.0.jar
[info] downloading https://repo1.maven.org/maven2/org/chipsalliance/chisel-plugin_2.13.18/7.7.0/chisel-plugin_2.13.18-7.7.0.jar
[info] downloading https://repo1.maven.org/maven2/org/apache/commons/commons-text/1.15.0/commons-text-1.15.0.jar
[info] downloading https://repo1.maven.org/maven2/org/chipsalliance/chisel_2.13/7.7.0/chisel_2.13-7.7.0.jar
[info] downloaded https://repo1.maven.org/maven2/io/github/json4s/json4s-ast_2.13/4.1.0/json4s-ast_2.13-4.1.0.jar
[info] downloading https://repo1.maven.org/maven2/io/github/json4s/json4s-scalap_2.13/4.1.0/json4s-scalap_2.13-4.1.0.jar
[info] downloaded https://repo1.maven.org/maven2/org/chipsalliance/chisel-plugin_2.13.18/7.7.0/chisel-plugin_2.13.18-7.7.0.jar
[info] downloading https://repo1.maven.org/maven2/io/github/json4s/json4s-core_2.13/4.1.0/json4s-core_2.13-4.1.0.jar
[info] downloaded https://repo1.maven.org/maven2/io/github/json4s/json4s-native-core_2.13/4.1.0/json4s-native-core_2.13-4.1.0.jar
[info] downloaded https://repo1.maven.org/maven2/org/chipsalliance/chisel_2.13/7.7.0/chisel_2.13-7.7.0.jar
[info] downloaded https://repo1.maven.org/maven2/io/github/json4s/json4s-scalap_2.13/4.1.0/json4s-scalap_2.13-4.1.0.jar
[info] downloaded https://repo1.maven.org/maven2/io/github/json4s/json4s-core_2.13/4.1.0/json4s-core_2.13-4.1.0.jar
[info] downloaded https://repo1.maven.org/maven2/org/apache/commons/commons-text/1.15.0/commons-text-1.15.0.jar
[info] downloading failed https://repo1.maven.org/maven2/io/github/json4s/json4s-native_2.13/4.1.0/json4s-native_2.13-4.1.0.jar
[info] downloading https://repo1.maven.org/maven2/io/github/json4s/json4s-native_2.13/4.1.0/json4s-native_2.13-4.1.0.jar.sha1
[info] downloaded https://repo1.maven.org/maven2/io/github/json4s/json4s-native_2.13/4.1.0/json4s-native_2.13-4.1.0.jar.sha1
[error] stack trace is suppressed; run 'last update' for the full output
  [error] stack trace is suppressed; run 'last ssExtractDependencies' for the full output
  [error] (update) lmcoursier.internal.shaded.coursier.error.FetchError$DownloadingArtifacts: Error fetching artifacts:
[error] https://repo1.maven.org/maven2/io/github/json4s/json4s-native_2.13/4.1.0/json4s-native_2.13-4.1.0.jar: download error: Caught java.net.SocketException (Connection reset) while downloading https://repo1.maven.org/maven2/io/github/json4s/json4s-native_2.13/4.1.0/json4s-native_2.13-4.1.0.jar
[error] (ssExtractDependencies) lmcoursier.internal.shaded.coursier.error.FetchError$DownloadingArtifacts: Error fetching artifacts:
[error] https://repo1.maven.org/maven2/io/github/json4s/json4s-native_2.13/4.1.0/json4s-native_2.13-4.1.0.jar: download error: Caught java.net.SocketException (Connection reset) while downloading https://repo1.maven.org/maven2/io/github/json4s/json4s-native_2.13/4.1.0/json4s-native_2.13-4.1.0.jar
[error] Total time: 9 s, completed Sep 18, 2026, 12:31:10 PM
  [info] shutting down sbt server

```


#### Short summary: 

empty definition using pc, found symbol in pc: 