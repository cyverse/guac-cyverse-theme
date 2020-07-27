# guac-cyverse-theme

A CyVerse/Jetstream theme for Apache Guacamole

## Instructions

1. Create the `guac-manifest.json` file for your desired domain:
  ```bash
  cp guac-manifest.cyverse.json guac-manifest.json
  cp guac-manifest.jetstream.json guac-manifest.json
  ```

2. Zip the files. Note that you zip the files and not the `guac-cyverse-theme` directory.
  ```
  zip -r theme.jar *
  ```

3. Add the jar to your guacamole extensions directory
