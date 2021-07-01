# open-broccoli
## Testing & linting

    ```
    ./gradlew lint testDebug
    ```

## Releasing
Releases are handled by CI. Releases are automatically made from the `release` branch.
Make sure to bump app version in `buildSrc/config.gradle` before releasing.

### Signing releases
To sign a release set the environment variable `SIGNING_PASSWORD` to the keystore password