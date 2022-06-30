# idea-4131802-scratch-files-not-running
Demonstrates issue reported in https://intellij-support.jetbrains.com/hc/requests/4131802

# Work-around

From (IntelliJ) Jun 30, 2022, 23:49 GMT+3:

Looks like https://youtrack.jetbrains.com/issue/IDEA-197627/Scratches-for-Java-do-not-work-when-Gradle-is-chosen-as-a-building-environment .

With https://i.imgur.com/HpeUaUE.png option it works: https://i.imgur.com/W1wlFF8.png .

To set this configuratino:

- CTRL+ALT+S -> Build, Execution, Deployment -> Build Tools -> Gradle
  - Build and run using: IntelliJ IDEA
  - Run tests using: IntelliJ IDEA
