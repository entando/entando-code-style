# entando-code-style
Purpose of this repository is to collect the
code-style rules we are adopting in Entando and
to propose updates to the rules that are accepted by
Entando's developers

## Import code style configuration on your favorite IDE
To make sure that the code written is formatted properly and adhere to Checkstyle rules,
we have created code style configuration for the 3 main Java IDEs (Intellij IDEA,
Apache NetBeans and Eclipse).

### Import the code style on Intellij IDEA
Go to **Settings -> Editor -> Code Style**. Click on the Gear Icon from the Scheme field
and select **Import Scheme -> Intellij IDEA code style XML**. Choose the Intellij configuration
file in config/intellij-java-entando-style.xml

### Import the code style on Apache NetBeans
Go to **Tools -> Options**. Click on **Import...** and choose the NetBeans configuration
file in config/netbeans-java-entando-style.zip

### Import the code style on Eclipse
Go to **Window -> Preferences -> Java -> Code Style -> Formatter** and click on **Import...**.
Choose the Eclipse configuration file in config/eclipse-java-entando-style.xml

After that go to **Window -> Preferences -> Java -> Code Style -> Organize Imports** and
remove everything from the Field **Define the sorting order of import...**

