fpm-maven-plugin
================

A Maven plugin to create system packages using FPM

```xml
  <plugin>
      <groupId>uk.me.ajmfulcher.fpmplugin</groupId>
      <artifactId>fpm-maven-plugin</artifactId>
      <configuration>
        <inputType>gem</inputType>
        <outputType>deb</outputType>
      </configuration>
      <executions>
        <execution>
            <id>run-fpm</id>
            <phase>package</phase>
            <goals>
                <goal>fpm</goal>
            </goals>
        </execution>
      </executions>
  </plugin>
```
