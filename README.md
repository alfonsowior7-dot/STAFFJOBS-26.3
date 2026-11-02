# STAFFJOBS 26.3

STAFFJOBS ported from the Paper 1.21.11 codebase to target Paper 26.3.

## Build requirements
- Java 25
- Gradle
- Paper API 26.3

## Build
```bash
gradle build
```

The plugin JAR is generated in `build/libs/`.

## Notes
- This repository targets Paper 26.3 only (`api-version: 26.3`).
- Plugin version: `1.3.8-26.3`.
- The original 1.21.11 repository remains separate.
- Runtime behavior and compilation must be validated through GitHub Actions and a test server before production use.
