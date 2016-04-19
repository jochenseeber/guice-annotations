# Guice Annotations

This project contains [external annotations](https://wiki.eclipse.org/JDT_Core/Null_Analysis/External_Annotations) for
[Guice](https://github.com/google/guice) version 4.0.

These annotations allow Eclipse to perform null analysis.

## Usage

To build the annotations JAR, run

```bash
gradle build
```

This will create the file `guice-annotations-4.0-r.1.jar`. Attach this file to the
Guice library entry in your build path to have Eclipse use the annotations.