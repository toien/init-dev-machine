### desc

used in maven 3, a java build tool.

- `archetype-catalog.xml`: local version of [catalog file](https://repo.maven.apache.org/maven2/archetype-catalog.xml), for mvn archetype plugin

  put in `USER_HOME/.m2` dir or `USER_HOME/.m2/repository` dir

- `*settings.xml`: maven settings file, defines repo mirror, active profile, repo account...  

  put in `USER_HOME/.m2` dir

maven needs to set some env vars to work fine, see `.&ast;shrc` under `USER_HOME` for details.
