# jo_sharedpreference
Simple. but most useful.

Data storage library for Android, using SharedPreference.

It has only 2 methods. Get and Push.
Usage is really simple. Check below codes out.

```java
//All data types are autocasted.
JoSharedPreference.with(this).push("paramString", "hello");
JoSharedPreference.with(this).push("paramInteger", 1);
JoSharedPreference.with(this).push("paramFloat", 1.0f);
JoSharedPreference.with(this).push("paramDouble", 2.2f);
JoSharedPreference.with(this).push("paramList", new ArrayList<>());
JoSharedPreference.with(this).push("paramCustom", new CustomModel());

String paramString = JoSharedPreference.with(this).get("paramString");
String paramInteger = JoSharedPreference.with(this).get("paramInteger");
String paramFloat = JoSharedPreference.with(this).get("paramFloat");
String paramDouble = JoSharedPreference.with(this).get("paramDouble");
String paramList = JoSharedPreference.with(this).get("paramList");
CustomModel paramCustom = JoSharedPreference.with(this).get("paramCustom");
```

