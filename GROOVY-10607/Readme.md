Compile it with `groovyc -j bar/foo/Bar.java bar/foo/Ban.java foo/bar/Foo.groovy`  
With groovy 3.0, it is fine.  
With groovy 4.0, this error appears  
```
/tmp/groovy-generated--java-source7060222205108938135/foo/bar/Foo.java:9: error: cannot find symbol
public static  java.lang.Object bar(Bar b) { return (java.lang.Object)null;}
                                    ^
  symbol:   class Bar
  location: class Foo
1 error

```
