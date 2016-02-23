I was looking for a simple SpringMVC demo than could quickly response a 'hello world' like message to me, from github.com, but I failed. I tried nearly two hours, with dozen of demo project, none can just let me type `something run` then open my browser to see the response.

So I create one, the code is originally from <http://www.mkyong.com/spring3/spring-3-mvc-hello-world-example/>, but I add the `build.gradle` to make it easy to launch.

## how to run ##

    ./gradlew jettyRun

   Which will download gradle and run it automatically.

The visit in your browse:

        http://localhost:8080/spring-mvc-demo/welcome

## how to develop on it ##

For idea, run:

        gradle idea

For eclipse, run:

        gradle eclipse

