* javax.json-1.1.jar contains both "JSR 374 : Java API for JSON Processing 1.1" API and its default provider implementation. Keep it in classpath for both compiling and running your application.

* If you are running with maven, you can use the following maven coordinates:

  <dependency>
      <groupId>org.glassfish</groupId>
      <artifactId>javax.json</artifactId>
      <version>1.1</version>
  </dependency>

* GlassFish 5.x already bundles latest JSON Processing implementation and JAX-RS integration module. If you deploy an application with GlassFish 5.x, your application (war/ear) doesn't have to bundle the ri jar.

* Samples can be run from https://github.com/javaee/glassfish-samples
