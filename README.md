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
* assertk: https://github.com/willowtreeapps/assertk 
* katz: Functional Data Types and abstractions for Kotlin https://github.com/FineCinnamon/Katz
* fuel: Kotlin Http Client
* kolor: A library to print colored strings https://github.com/ziggy42/kolor
* kotlin-futures: A collections of extension functions to make the JVM Future, CompletableFuture, ListenableFuture API more functional and Kotlin like. https://github.com/vjames19/kotlin-futures
* kotlinpoet: A Kotlin API for generating .kt source files
* Physikal: https://github.com/Tenkiv/Physikal
* kotlinx.atomicfu: The idiomatic way to use atomic operations in Kotlin
* date&time DSL： khronos， kizitonwose/Time 
* MockK: mocking library for Kotlin http://mockk.io/
* human-readable Kotlin DSL for IPCs & turning anything into a message receiver / broadcaster: https://github.com/DavidMellul/Kotlin-Publish-Subscribe
* KDispatcher is a Kotlin EventDispatcher https://github.com/Rasalexman/KDispatcher
* Kotlin dsl for spring mvc test： https://github.com/petrbalat/kd4smt
* Klock: Klock is a Date & Time library for Multiplatform Kotlin 1.3 https://korlibs.soywiz.com/klock/
* SpringMockK: MockBean and SpyBean, but for MockK instead of Mockito： https://github.com/Ninja-Squad/springmockk
* Strikt: assertion library for Kotlin intended for use with a test runner: https://strikt.io/
* mapdb: MapDB provides concurrent Maps, Sets and Queues backed by disk storage or off-heap-memory https://github.com/jankotek/mapdb
* fakeit: The Kotlin fake data generator library https://github.com/moove-it/fakeit
* The simple, stupid random Java beans generator: https://github.com/j-easy/easy-random
* Kotlin Multiplatform Arithmatic Parser:  https://github.com/KaenDagger/KParser
* dataframe: Structured data processing in Kotlin - https://github.com/Kotlin/dataframe

### References

* https://kotlin.link/
* https://github.com/KotlinBy/awesome-kotlin
* The Kotlin Programming Language: https://caster.io/courses/kotlin-programming-language
