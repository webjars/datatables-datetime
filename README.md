# DataTables DateTime WebJar (datatables-datetime)

[DataTables DateTime](https://github.com/DataTables/DateTime) is an extension for DataTables that
provide a user friendly way to select values for dates and times. This [WebJar](https://webjars.org) includes the
corresponding JavaScript and CSS files. [DataTables](https://datatables.net/) and the DateTime extension
are provided by [SpryMedia Ltd. Scotland](https://sprymedia.co.uk/) under the
[MIT License](https://github.com/DataTables/DateTime/blob/master/license.txt).

WebJars are usually built using a plain Maven POM. This WebJar uses the
[Wagon Maven Plugin](https://www.mojohaus.org/wagon-maven-plugin/) to download the DataTables DateTime files from
jsDelivr and puts them into the Java archive.

## Usage

Just include this WebJar into your project. For Maven, you can use the following snippet:

```xml
<dependency>
    <groupId>org.webjars</groupId>
    <artifactId>datatables-datetime</artifactId>
    <version>1.0.1</version>
</dependency>
```

And here is a Gradle snippet for you:

```groovy
implementation 'org.webjars:datatables-datetime:1.0.1'
```

## Building

Just call

    mvn clean install

and the Jar is built. You can check the output in the target folder. Please make sure that all
required files are included and have proper content.

## Contributing

I highly welcome your updates and improvements. Please open a pull request if you want to contribute
to the DataTables DateTime WebJar. Thanks in advance!
