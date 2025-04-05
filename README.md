Add it in your settings.gradle.kts at the end of repositories:

	dependencyResolutionManagement {
		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
		repositories {
			mavenCentral()
			maven { url = uri("https://jitpack.io") }
		}
	}
Step 2. Add the dependency

	dependencies {
	        implementation("com.github.Kratos1996:utilLibToolkit:Tag")
	}
Share this release:   [![](https://jitpack.io/v/Kratos1996/utilLibToolkit.svg)](https://jitpack.io/#Kratos1996/utilLibToolkit)

Link
That's it! The first time you request a project JitPack checks out the code, builds it and serves the build artifacts (jar, aar).

If the project doesn't have any GitHub Releases you can use the short commit hash or 'master-SNAPSHOT' as the version.
