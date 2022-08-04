# Velocity (KettleMC.net Fork)

A Minecraft server proxy with unparalleled server support, scalability,
and flexibility.

- Forked by [EnvyWare](https://github.com/EnvyWare/Velocity) to add modern Forge compatibility.
- Forked by [KettleMC.net](https://discord.gg/f9P9HEj) in order to add some features for our network.

[Velocity](https://github.com/PaperMC/Velocity) is licensed under the GPLv3 license.
  
## Building

Velocity is built with [Gradle](https://gradle.org). We recommend using the
wrapper script (`./gradlew`) as our CI builds using it.

It is sufficient to run `./gradlew build` to run the full build cycle.

## Running

Once you've built Velocity, you can copy and run the `-all` JAR from
`proxy/build/libs`. Velocity will generate a default configuration file
and you can configure it from there.
