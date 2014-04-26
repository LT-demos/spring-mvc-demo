I was looking for a simple SpringMVC demo than could quickly response a 'hello world' like message to me, from github.com, but I failed. I tried nearly two hours, with dozen of demo project, none can just let me type `something run` then open my browser to see the response.

So I create one, the code is originally from <http://www.mkyong.com/spring3/spring-3-mvc-hello-world-example/>, but I add the `build.gradle` to make it easy to launch.

## how to run ##

1. Clone the project to your local computer

        git clone https://github.com/freewind/SpringMVCDemo.git

2. If you have installed `gradle`, just run:

        gradle jettyRun

3. otherwise, run:

        ./gradlew jettyRun

   Which will download gradle and run it automatically.

4. Finally, open your browser, visit:

        http://localhost:8080/SpringMVCDemo/welcome

## how to develop on it ##

For idea, run:

        gradle idea

For eclipse, run:

        gradle eclipse

