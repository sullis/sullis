# My openrewrite Contributions

Merged pull requests authored by [@sullis](https://github.com/sullis) across the [openrewrite](https://github.com/openrewrite) organization.

_Generated 2026-10-16 from the GitHub search API._

## Summary

- **Merged pull requests:** 116
- **Repositories:** 16

| Repository | Merged PRs |
|---|---:|
| [openrewrite/rewrite](#openrewriterewrite) | 27 |
| [openrewrite/rewrite-jackson](#openrewriterewrite-jackson) | 18 |
| [openrewrite/rewrite-testing-frameworks](#openrewriterewrite-testing-frameworks) | 16 |
| [openrewrite/rewrite-migrate-java](#openrewriterewrite-migrate-java) | 13 |
| [openrewrite/rewrite-apache](#openrewriterewrite-apache) | 9 |
| [openrewrite/rewrite-maven-plugin](#openrewriterewrite-maven-plugin) | 9 |
| [openrewrite/rewrite-logging-frameworks](#openrewriterewrite-logging-frameworks) | 8 |
| [openrewrite/rewrite-netty](#openrewriterewrite-netty) | 4 |
| [openrewrite/rewrite-github-actions](#openrewriterewrite-github-actions) | 3 |
| [openrewrite/rewrite-docs](#openrewriterewrite-docs) | 2 |
| [openrewrite/rewrite-spring](#openrewriterewrite-spring) | 2 |
| [openrewrite/rewrite-gradle-plugin](#openrewriterewrite-gradle-plugin) | 1 |
| [openrewrite/rewrite-java-8](#openrewriterewrite-java-8) | 1 |
| [openrewrite/rewrite-jenkins](#openrewriterewrite-jenkins) | 1 |
| [openrewrite/rewrite-recipe-bom](#openrewriterewrite-recipe-bom) | 1 |
| [openrewrite/rewrite-static-analysis](#openrewriterewrite-static-analysis) | 1 |

## openrewrite/rewrite

| Merged | PR | Title |
|---|---|---|
| 2026-10-16 | [#9155](https://github.com/openrewrite/rewrite/pull/9155) | Add Gradle RemoveDuplicateDependencies recipe |
| 2026-10-16 | [#9083](https://github.com/openrewrite/rewrite/pull/9083) | Gradle: add RemoveExtraProperty recipe |
| 2026-09-16 | [#8878](https://github.com/openrewrite/rewrite/pull/8878) | Don't apply UsePropertyAssignmentSyntax to version catalog builders |
| 2026-09-14 | [#8802](https://github.com/openrewrite/rewrite/pull/8802) | Flag usage of lombok val and var as an error |
| 2026-08-03 | [#8358](https://github.com/openrewrite/rewrite/pull/8358) | Fix OneDependencyDeclarationPerStatement mangling DependencyHandler.add() calls |
| 2026-07-26 | [#8329](https://github.com/openrewrite/rewrite/pull/8329) | Add Gradle recipe `RemoveEmptyBuildscriptBlock` |
| 2026-07-06 | [#8177](https://github.com/openrewrite/rewrite/pull/8177) | use gradle property assignment for distributionUrl |
| 2026-06-15 | [#8013](https://github.com/openrewrite/rewrite/pull/8013) | Add mockk to IsLikelyTest |
| 2026-06-15 | [#7957](https://github.com/openrewrite/rewrite/pull/7957) | Add unit test for junit-bom upgrade |
| 2026-05-13 | [#7612](https://github.com/openrewrite/rewrite/pull/7612) | Use version closure in MigrateToGradle9 |
| 2026-05-12 | [#7596](https://github.com/openrewrite/rewrite/pull/7596) | Use application mainClass in MigrateToGradle9 |
| 2026-04-28 | [#7504](https://github.com/openrewrite/rewrite/pull/7504) | Migrate 'main' property in MigrateToGradle9 |
| 2026-04-28 | [#7481](https://github.com/openrewrite/rewrite/pull/7481) | Add unit test for lombok.val |
| 2026-03-10 | [#6907](https://github.com/openrewrite/rewrite/pull/6907) | Add tests for Gradle 9 migration and best practices recipes |
| 2025-11-04 | [#6249](https://github.com/openrewrite/rewrite/pull/6249) | add tools.jackson to protected prefix list |
| 2025-10-02 | [#6096](https://github.com/openrewrite/rewrite/pull/6096) | Use Maven repository credentials in `GradleProjectBuilder` |
| 2025-05-15 | [#5428](https://github.com/openrewrite/rewrite/pull/5428) | Add assertions in PathUtilsTest |
| 2025-05-14 | [#5426](https://github.com/openrewrite/rewrite/pull/5426) | Add additional test case to gradle AddPropertyTest |
| 2025-04-21 | [#5316](https://github.com/openrewrite/rewrite/pull/5316) | Add additional test case for Gradle AddProperty recipe |
| 2024-12-17 | [#4788](https://github.com/openrewrite/rewrite/pull/4788) | enhance UpgradeDependencyVersionTest |
| 2023-04-23 | [#3151](https://github.com/openrewrite/rewrite/pull/3151) | remove semicolons from RemoveUnusedVisitorTest |
| 2023-04-18 | [#3136](https://github.com/openrewrite/rewrite/pull/3136) | AppendToSequence: improve handling of scalar values |
| 2023-04-14 | [#2942](https://github.com/openrewrite/rewrite/pull/2942) | new YAML recipe: AppendToSequence |
| 2022-12-30 | [#2578](https://github.com/openrewrite/rewrite/pull/2578) | new unit test: addDependencyWithClassifier |
| 2022-12-29 | [#2573](https://github.com/openrewrite/rewrite/pull/2573) | unit test for sealed interfaces |
| 2020-08-22 | [#24](https://github.com/openrewrite/rewrite/pull/24) | kotlin 1.4.0 |
| 2020-07-27 | [#4](https://github.com/openrewrite/rewrite/pull/4) | add Gradle wrapper validation |

## openrewrite/rewrite-jackson

| Merged | PR | Title |
|---|---|---|
| 2026-01-19 | [#78](https://github.com/openrewrite/rewrite-jackson/pull/78) | Upgrade `jackson-annotations` to `2.21 |
| 2025-11-17 | [#48](https://github.com/openrewrite/rewrite-jackson/pull/48) | cleanup UpgradeJackson_2_3Test |
| 2025-11-13 | [#47](https://github.com/openrewrite/rewrite-jackson/pull/47) | Use wildcards to convert all artifacts under dataformat and module |
| 2025-11-13 | [#44](https://github.com/openrewrite/rewrite-jackson/pull/44) | support jackson-module-kotlin |
| 2025-10-31 | [#36](https://github.com/openrewrite/rewrite-jackson/pull/36) | readme: why upgrade to jackson 3 |
| 2025-10-13 | [#28](https://github.com/openrewrite/rewrite-jackson/pull/28) | support jackson-dataformat-yaml migration |
| 2025-10-04 | [#26](https://github.com/openrewrite/rewrite-jackson/pull/26) | update for jackson 3.0.0 GA |
| 2025-09-20 | [#22](https://github.com/openrewrite/rewrite-jackson/pull/22) | update for jackson 3.0.0-rc10 |
| 2025-09-08 | [#19](https://github.com/openrewrite/rewrite-jackson/pull/19) | update for jackson 3.0 rc9 |
| 2025-08-17 | [#18](https://github.com/openrewrite/rewrite-jackson/pull/18) | update for jackson 3.0.0-rc8 |
| 2025-08-10 | [#17](https://github.com/openrewrite/rewrite-jackson/pull/17) | update for jackson 3.0.0-rc7 |
| 2025-07-20 | [#15](https://github.com/openrewrite/rewrite-jackson/pull/15) | update for jackson 3.0.0-rc6 |
| 2025-06-09 | [#10](https://github.com/openrewrite/rewrite-jackson/pull/10) | logback.xml -> logback-test.xml |
| 2025-05-27 | [#8](https://github.com/openrewrite/rewrite-jackson/pull/8) | upgrade to jackson 3.0 rc5 |
| 2025-05-14 | [#7](https://github.com/openrewrite/rewrite-jackson/pull/7) | add category.yml |
| 2025-05-13 | [#5](https://github.com/openrewrite/rewrite-jackson/pull/5) | fix: jackson annotations package |
| 2025-05-13 | [#3](https://github.com/openrewrite/rewrite-jackson/pull/3) | Add recipe for Jackson 3 |
| 2025-05-13 | [#2](https://github.com/openrewrite/rewrite-jackson/pull/2) | Fix build.gradle.kts |

## openrewrite/rewrite-testing-frameworks

| Merged | PR | Title |
|---|---|---|
| 2026-10-12 | [#1184](https://github.com/openrewrite/rewrite-testing-frameworks/pull/1184) | WireMock 4 migration: move Jetty EE10 to EE11 and bump to 4.0.0-beta.40 |
| 2026-09-29 | [#1122](https://github.com/openrewrite/rewrite-testing-frameworks/pull/1122) | Add WireMock 3 to 4 migration recipe |
| 2026-05-26 | [#1006](https://github.com/openrewrite/rewrite-testing-frameworks/pull/1006) | Add RemoveJupiterMigrationSupport recipe |
| 2026-05-08 | [#993](https://github.com/openrewrite/rewrite-testing-frameworks/pull/993) | Cleanup junit vintage engine |
| 2026-05-08 | [#994](https://github.com/openrewrite/rewrite-testing-frameworks/pull/994) | Add unit test for JUnit6BestPractices |
| 2026-04-28 | [#977](https://github.com/openrewrite/rewrite-testing-frameworks/pull/977) | Cleanup Mockito AutoCloseable fields |
| 2025-10-17 | [#830](https://github.com/openrewrite/rewrite-testing-frameworks/pull/830) | Change dependencies and types for testcontainers v2 |
| 2025-09-30 | [#821](https://github.com/openrewrite/rewrite-testing-frameworks/pull/821) | remove dependency: google truth |
| 2025-09-26 | [#822](https://github.com/openrewrite/rewrite-testing-frameworks/pull/822) | truth migration adds assertj-core |
| 2025-08-30 | [#801](https://github.com/openrewrite/rewrite-testing-frameworks/pull/801) | verify that junit vintage engine is removed |
| 2025-06-18 | [#750](https://github.com/openrewrite/rewrite-testing-frameworks/pull/750) | testcontainers 1.21.x |
| 2024-12-24 | [#657](https://github.com/openrewrite/rewrite-testing-frameworks/pull/657) | improve assertions in Mockito1to5MigrationTest |
| 2024-12-23 | [#656](https://github.com/openrewrite/rewrite-testing-frameworks/pull/656) | Add `Mockito1to5MigrationTest` to verify dependencies are upgraded |
| 2024-12-19 | [#651](https://github.com/openrewrite/rewrite-testing-frameworks/pull/651) | add Mockito1to4MigrationTest |
| 2024-11-17 | [#641](https://github.com/openrewrite/rewrite-testing-frameworks/pull/641) | don't exclude junit4 for testcontainers jupiter |
| 2022-12-31 | [#294](https://github.com/openrewrite/rewrite-testing-frameworks/pull/294) | fix abstract class logic in TestsShouldNotBePublic |

## openrewrite/rewrite-migrate-java

| Merged | PR | Title |
|---|---|---|
| 2026-09-25 | [#1245](https://github.com/openrewrite/rewrite-migrate-java/pull/1245) | Add `MigrateFromSpotBugsAnnotations` recipe |
| 2026-09-22 | [#1244](https://github.com/openrewrite/rewrite-migrate-java/pull/1244) | Add a `FlagUsage` recipe to stop Lombok's `val`/`var` from coming back |
| 2026-09-21 | [#1242](https://github.com/openrewrite/rewrite-migrate-java/pull/1242) | Create root `lombok.config` when a project has none |
| 2026-09-18 | [#1236](https://github.com/openrewrite/rewrite-migrate-java/pull/1236) | Add lombok.config recipes |
| 2026-09-11 | [#1237](https://github.com/openrewrite/rewrite-migrate-java/pull/1237) | Fix annotation handling in `LombokValToFinalVar` |
| 2026-09-03 | [#1232](https://github.com/openrewrite/rewrite-migrate-java/pull/1232) | Do not add `final` to a try-with-resources resource |
| 2026-09-03 | [#1233](https://github.com/openrewrite/rewrite-migrate-java/pull/1233) | Preserve casts when converting `lombok.val` to `final var` |
| 2026-09-02 | [#1230](https://github.com/openrewrite/rewrite-migrate-java/pull/1230) | Improve test coverage for LombokValToFinalVar |
| 2026-05-03 | [#1076](https://github.com/openrewrite/rewrite-migrate-java/pull/1076) | Add jspecify hyperlink |
| 2024-10-09 | [#572](https://github.com/openrewrite/rewrite-migrate-java/pull/572) | Migrate Spring annotations to JSpecify |
| 2024-09-03 | [#543](https://github.com/openrewrite/rewrite-migrate-java/pull/543) | Recipe to migrate from `Math.random` to `ThreadLocalRandom` |
| 2024-08-30 | [#541](https://github.com/openrewrite/rewrite-migrate-java/pull/541) | Recipes to migrate from Javax, Jakarta and JetBrains nullability annotations to JSpecify |
| 2023-01-09 | [#163](https://github.com/openrewrite/rewrite-migrate-java/pull/163) | add unit test for recipe UpgradeToJava17 |

## openrewrite/rewrite-apache

| Merged | PR | Title |
|---|---|---|
| 2026-10-12 | [#153](https://github.com/openrewrite/rewrite-apache/pull/153) | Upgrade HttpClient 5 migration target to 5.6.x |
| 2026-08-12 | [#144](https://github.com/openrewrite/rewrite-apache/pull/144) | Add `ApacheBestPractices` and `ApacheCommonsBestPractices` recipes |
| 2024-11-15 | [#40](https://github.com/openrewrite/rewrite-apache/pull/40) | use Apache HttpClient 5.4.x |
| 2024-06-10 | [#19](https://github.com/openrewrite/rewrite-apache/pull/19) | use Apache HttpClient 5.x ClassicRequestBuilder |
| 2024-06-07 | [#18](https://github.com/openrewrite/rewrite-apache/pull/18) | use Apache HttpClient 5.3.x |
| 2024-03-28 | [#13](https://github.com/openrewrite/rewrite-apache/pull/13) | add recipe for Apache Commons Math 3.x |
| 2024-03-28 | [#11](https://github.com/openrewrite/rewrite-apache/pull/11) | replace Apache Commons Collections FastArrayList |
| 2024-03-28 | [#12](https://github.com/openrewrite/rewrite-apache/pull/12) | add recipe for upgrading to Apache Commons Lang 3 |
| 2024-03-27 | [#10](https://github.com/openrewrite/rewrite-apache/pull/10) | add recipe for Apache Commons Collections |

## openrewrite/rewrite-maven-plugin

| Merged | PR | Title |
|---|---|---|
| 2022-06-06 | [#371](https://github.com/openrewrite/rewrite-maven-plugin/pull/371) | bumping Java version to 17 |
| 2022-04-03 | [#321](https://github.com/openrewrite/rewrite-maven-plugin/pull/321) | Maven wrapper upgrade |
| 2021-03-27 | [#107](https://github.com/openrewrite/rewrite-maven-plugin/pull/107) | fix version number in README.md |
| 2021-03-07 | [#90](https://github.com/openrewrite/rewrite-maven-plugin/pull/90) | stop using bintray.com |
| 2020-11-07 | [#36](https://github.com/openrewrite/rewrite-maven-plugin/pull/36) | ci: automerge Dependabot pull requests |
| 2020-08-30 | [#37](https://github.com/openrewrite/rewrite-maven-plugin/pull/37) | upgrade to maven-surefire-plugin 3.0.0-M5 |
| 2020-08-10 | [#23](https://github.com/openrewrite/rewrite-maven-plugin/pull/23) | ci: mvn --no-transfer-progress |
| 2020-07-11 | [#3](https://github.com/openrewrite/rewrite-maven-plugin/pull/3) | enable Dependabot v2 |
| 2020-07-11 | [#2](https://github.com/openrewrite/rewrite-maven-plugin/pull/2) | enable GitHub Actions CI |

## openrewrite/rewrite-logging-frameworks

| Merged | PR | Title |
|---|---|---|
| 2022-11-29 | [#84](https://github.com/openrewrite/rewrite-logging-frameworks/pull/84) | Log4j1ToSlf4j1Test: test case for static final loggers |
| 2022-11-20 | [#83](https://github.com/openrewrite/rewrite-logging-frameworks/pull/83) | additional test case for Slf4jBestPracticesTest |
| 2022-10-31 | [#78](https://github.com/openrewrite/rewrite-logging-frameworks/pull/78) | Log4j1ToLog4j2 recipe replaces slf4j binding |
| 2022-10-29 | [#77](https://github.com/openrewrite/rewrite-logging-frameworks/pull/77) | recipe Log4j1ToLog4j2 removes reload4j dependency |
| 2022-10-24 | [#75](https://github.com/openrewrite/rewrite-logging-frameworks/pull/75) | simplify Slf4jBestPracticesTest |
| 2022-10-24 | [#76](https://github.com/openrewrite/rewrite-logging-frameworks/pull/76) | add Logger usage test case to Log4j2ToSlf4j1Test |
| 2022-10-23 | [#73](https://github.com/openrewrite/rewrite-logging-frameworks/pull/73) | add Slf4j Best Practices recipe |
| 2020-07-13 | [#1](https://github.com/openrewrite/rewrite-logging-frameworks/pull/1) | chmod +x gradlew |

## openrewrite/rewrite-netty

| Merged | PR | Title |
|---|---|---|
| 2025-09-16 | [#9](https://github.com/openrewrite/rewrite-netty/pull/9) | add category tags |
| 2025-09-16 | [#8](https://github.com/openrewrite/rewrite-netty/pull/8) | validate io_uring artifacts |
| 2025-06-19 | [#3](https://github.com/openrewrite/rewrite-netty/pull/3) | update README |
| 2025-06-16 | [#1](https://github.com/openrewrite/rewrite-netty/pull/1) | netty 4.2 recipe |

## openrewrite/rewrite-github-actions

| Merged | PR | Title |
|---|---|---|
| 2024-04-13 | [#98](https://github.com/openrewrite/rewrite-github-actions/pull/98) | enhance unit test for SetupJavaUpgradeJavaVersion |
| 2024-04-13 | [#99](https://github.com/openrewrite/rewrite-github-actions/pull/99) | support setup-java v4 |
| 2022-03-29 | [#16](https://github.com/openrewrite/rewrite-github-actions/pull/16) | support setup-java v2 and v3 |

## openrewrite/rewrite-docs

| Merged | PR | Title |
|---|---|---|
| 2024-10-30 | [#314](https://github.com/openrewrite/rewrite-docs/pull/314) | use latest.release |
| 2022-10-11 | [#93](https://github.com/openrewrite/rewrite-docs/pull/93) | update Gradle plugin examples |

## openrewrite/rewrite-spring

| Merged | PR | Title |
|---|---|---|
| 2024-11-26 | [#641](https://github.com/openrewrite/rewrite-spring/pull/641) | fix test dontEnableVirtualThreadsIfDisabled |
| 2021-05-29 | [#73](https://github.com/openrewrite/rewrite-spring/pull/73) | gradle 7.0.2 |

## openrewrite/rewrite-gradle-plugin

| Merged | PR | Title |
|---|---|---|
| 2020-08-09 | [#2](https://github.com/openrewrite/rewrite-gradle-plugin/pull/2) | add Gradle wrapper validation |

## openrewrite/rewrite-java-8

| Merged | PR | Title |
|---|---|---|
| 2020-08-31 | [#1](https://github.com/openrewrite/rewrite-java-8/pull/1) | enable Gradle wrapper validation |

## openrewrite/rewrite-jenkins

| Merged | PR | Title |
|---|---|---|
| 2023-06-05 | [#3](https://github.com/openrewrite/rewrite-jenkins/pull/3) | cleanup GitHub Actions |

## openrewrite/rewrite-recipe-bom

| Merged | PR | Title |
|---|---|---|
| 2025-05-13 | [#39](https://github.com/openrewrite/rewrite-recipe-bom/pull/39) | add rewrite-jackson |

## openrewrite/rewrite-static-analysis

| Merged | PR | Title |
|---|---|---|
| 2026-09-17 | [#1046](https://github.com/openrewrite/rewrite-static-analysis/pull/1046) | Add UnnecessaryFinalInTryWithResources |
