Finalsite JRuby Docker Image
===================

1. Update 9000/alpine-jdk/Dockerfile to the desired java/jruby versions
2. Build and tag the container: `docker build . -t {dev docker repo}/builds/jruby:{jrubyversion}-jdk-alpine`
3. Push the new image: `docker push {dev docker repo}/builds/jruby:{jrubyversion}-jdk-alpine`
