Compile it with `groovyc -j bar/foo/Bar.java bar/foo/Ban.java foo/bar/Foo.groovy`  
With groovy 3.0, it is fine.  
With groovy 4.0, this error appears  
```
org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
foo/bar/Foo.groovyls: foo/bar/Foo.groovyls (No such file or directory)

1 error
```
