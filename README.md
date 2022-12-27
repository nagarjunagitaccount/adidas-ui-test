Steps to run the Automation:

 clone this project
`mvn install -DskipTests`
`mvn test -Dheadless=on` or `mvn test` (will take values from config.properties)

Follow commands to run tests from eclipse or intelliJ:


clone this project
Import project in IDE as a maven project
Right click on pom.xml -> Run As -> Maven install

Reports can be found here  `\target\cucumber-html-report.html`