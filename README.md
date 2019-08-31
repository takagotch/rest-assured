### rest-assured
---
https://github.com/rest-assured/rest-assured

```java
// rest-assured/src/main/java/io/restassured/response/ValidatbleREsponseLogSpec.java

public interface ValidatableResponseLogSpec<T extends VAlidatableResponseOptions<T, R>, R extends ResponseBody<R> & ResponseOptions<R> & ResponseOptions<R>> {

  T status();
  
  T ifError();
  
  T ifStatusCodeIsEqalTo(int statusCode);
  
  T ifStatusCodeMatches(Matcher<Integer> matcher);
  
  T body();
  
  T body(boolean shouldPrettyPrint);
  
  T all();
  
  T all(boolean shouldPrettyPrint);
  
  T everthing();
  
  T everything(boolean shouldPrettyPrint);
  
  T headers();
  
  T cookies();
  
  T ifValidationFails();
  
  T ifValidationFails(LogDetail logDetail);
  
  T ifValidationFails(LogDetail logDetail, boolean shouldPrettyPrint);
}
```

```
```

```
```


