# Hyperswitch HTML + Java Integration

Build a simple checkout form to collect payment details. Included are some basic
build and run scripts you can use to start up the application.

## Running the sample

1. Add your keys :
    - Navigate to `public/script.js` and replace the placeholder `HYPERSWITCH_PUBLISHABLE_KEY` with your publishable key.
    - Navigate to `src/main/java/com/hyperswitch/sample/server.java` and replace the placeholder `HYPERSWITCH_API_KEY` with your API key.

2. Install the dependencies :
~~~
mvn package
~~~

3. Run the server :
~~~
java -cp target/sample-jar-with-dependencies.jar com.hyperswitch.sample.server
~~~

4. The sample app is now accessible here : [http://localhost:4242/index.html](http://localhost:4242/index.html).