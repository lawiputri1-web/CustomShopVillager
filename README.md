# Custom Villager Shops — Command Shop prototype

Minecraft Java 1.21.11 / Fabric / Java 21.

## Features intended by this source project
- `/shop` prints clickable profession choices.
- `/shop librarian`, `/shop armorer`, `/shop butcher`, `/shop fletcher`, `/shop mason`, `/shop shepherd`, `/shop toolsmith`, `/shop weaponsmith` opens a vanilla merchant trade screen using a temporary villager.
- Existing shop data functions from the supplied JAR are preserved.
- Temporary tagged villagers are discarded after the trade screen closes.

## Build
Run `gradle clean build` with Java 21 and Gradle 9.2.1 or use the included GitHub Actions workflow. The JAR should appear under `build/libs/`.

## Important
This is a source conversion/prototype created from the supplied compiled JAR, not a tested final JAR. The build workflow must pass and the resulting JAR must be tested in a copied world before use in a Hardcore world. If compilation fails, use the GitHub Actions error log to correct API mapping/version differences.
