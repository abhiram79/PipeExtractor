## PipeExtractor
[![](https://jitpack.io/v/abhiram79/PipeExtractor.svg)](https://jitpack.io/#abhiram79/PipeExtractor)
<br>
[Get Flowtune](https://github.com/abhiram79/Flowtune)



# Gradle
- root settings.gradle
```bash 
dependencyResolutionManagement {
		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
		repositories {
			mavenCentral()
			maven { url 'https://jitpack.io' }
		}
	}
```
- Add the dependency
```bash
dependencies {
	        implementation 'com.github.abhiram79.PipeExtractor:PipeExtractor:1.0'
	}
```


# Gradle.kts
- settings.gradle.kts
```bash
dependencyResolutionManagement {
		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
		repositories {
			mavenCentral()
			maven { url = uri("https://jitpack.io") }
		}
	}
```
- Add the dependency
```bash
dependencies {
	        implementation("com.github.abhiram79.PipeExtractor:PipeExtractor:1.0")
	}
```
