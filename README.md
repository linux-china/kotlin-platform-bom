Kotlin Platform BOM
===================

A BOM for Kotlin platform

### How to use ?

Please add following code in your pom.xml:

```xml
<dependencyManagement>
     <dependencies>
         <dependency>
             <groupId>com.github.linux-china</groupId>
             <artifactId>kotlin-platform-bom</artifactId>
             <version>1.0.0-SNAPSHOT</version>
             <type>pom</type>
             <scope>import</scope>
         </dependency>
     </dependencies>
 </dependencyManagement>
```

### Artifacts

* assertj-core-kotlin
```kotlin
import org.assertj.core.api.KotlinAssertions.assertThat
import org.junit.Test

class KotlinAssertionsExample {
    @Test
    fun simpleAssertion() {
        assertThat(10L.toString()).isEqualTo("10")
    }
}
```

### References

* https://kotlin.link/
* https://github.com/KotlinBy/awesome-kotlin