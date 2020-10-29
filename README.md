# fhir-cicd-common
Common assets for automated integration / deployment

### settings.xml

Used for authentication against mulesoft nexus, exchange, and github. Use organization level secrets to pass in authentication. For local work, you can use this settings.xml in your `~/.m2/` directory, subtituting the environment variables with your own information. You will need to fill in your nexus username & password, exchange username & password, and then generate a GITHUB token with `packages:read`.
