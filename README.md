# eb test

this is just a VERY simple socket-based echo server, running on amazon elastic beanstalk in nodejs with socket.io

to run this test:

1. install node dependendencies with `npm install`
2. launch the app with `node app.js`
3. point your browser to http://localhost:8888

![running app](img/02_app.png?raw=true "echo socket server")

to install it on elastic beanstalk, follow the guide linked in the ref section of this doc, then disable nginx proxy as shown in the screenshot below

![aws](img/01_proxy.png?raw=true "eb console - disable proxy")

## ref

- develop & deploy, guides for nodejs, ruby, python, php and java on tomcat. http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create_deploy_nodejs.sdlc.html

- disable proxy when running socket.io: http://stackoverflow.com/questions/15907302/websockets-with-socket-io-on-aws-elastic-beanstalk
