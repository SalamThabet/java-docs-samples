# Getting Started with Google Cloud Speech API and the Google Cloud Client libraries

[Google Cloud Speech API][speech] enables easy integration of Google speech
recognition technologies into developer applications.

These sample Java applications demonstrate how to access the Cloud Speech API
using the [Google Cloud Client Library for Java][google-cloud-java].

[speech]: https://cloud.google.com/speech/docs/
[google-cloud-java]: https://github.com/GoogleCloudPlatform/google-cloud-java

## Quickstart

Install [Maven](http://maven.apache.org/).

Build your project with:

  mvn clean package -DskipTests

You can then run a given `ClassName` via:

  mvn exec:java -Dexec.mainClass=com.example.speech.ClassName \
      -DpropertyName=propertyValue \
    -Dexec.args="arg1 'arg 2' arg3"

### Transcribe a local audio file (using the quickstart sample)

    mvn exec:java -Dexec.mainClass=com.example.speech.QuickstartSample
