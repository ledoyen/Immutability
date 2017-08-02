# Keep It Stupid Simple in Java

Using [Lombok](https://projectlombok.org)
```java
@Value
@Builder
@ToString(includeFieldNames=true)
public class ValueExample {
  String name;
  int age;
  double score;
  String[] tags;
}
```

Using [Immutables](https://immutables.github.io)
```java
@Value.Immutable
public interface ValueExample {
  String name();
  int age();
  double score();
  String[] tags();
}
```