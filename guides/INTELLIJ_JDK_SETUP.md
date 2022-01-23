# IntelliJ JDK setup


We will be installing Java (JDK) through IntelliJ directly.

**You may already have Java installed through your platform's package manager, we won't be using that for portability reasons.**


## Installing JDK via IntellJ

First, launch IntelliJ, you should see the following window.

Select `New project` on the top right.

In the `New project` dialog, click the `Project SDK` dropdown and select `Download JDK`.


Make sure you configure the `Download JDK` dialog as follows:

 * Version: 17
 * Vendor: Oracle OpenJDK
 * Location: (leave default, don't modify)

Click download and wait for installation to complete.
Once installed, the `Project SDK` dropdown should now show the JDK you have just installed.

Click `Next` in the `New project` dialog, make sure *not* to check anything in the `Additional libraries and frameworks`, leave everything default here.

Check `Create project from template` and click `Next`.

Set the `Project name` to `hello` and make note of the project location.
Keep everything else default and click `Finish`.
IntelliJ will setup a new project, this may take a few minutes.


Once completed, type the line `System.out.println("Hello world!")` after  `// write your code here`.

Click the green play button on the top right and observe program output.


## Adding JDK to PATH

Now that we have our JDK installed through IntelliJ, we need to add it to PATH for `java`, `javac` and all other Java related commands to work.

First, find out where the JDK you've installed through IntelliJ is located.

<!-- TODO finish up -->

