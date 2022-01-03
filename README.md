# Builds latest Spigot 1.8.8 - Download .jar from actions or releases

# SpigotBuildAction
Spigot Build Action is a simple GitHub Action project, for the server owners who cannot build Spigot on their own computer. You can download the spigot.jar in every build action.

## Other versions:
You can get the other version by doing following steps:

1. Fork this repository. (Maybe leave a star)
1. Edit the `buildspigot-buildtools.yml` in `.github/workflows`. Change `--rev 1.8.8` to `--rev [the version]` and change `java-version: "8"` to `java-version: "17"` if you're building Minecraft version >= `1.17`.
1. Push the changed files.
1. Go to Actions, Workflows, All workflows, BuildSpigot with Latest BuildTools, and Run workflow.
1. Wait for the action done.
1. Download the artifact from the action.
