# easycode

源文件user.ef

```
def model
{
	def User 
	{
		id(type = String)
		name(type = String)
		address(type = String)
	}
	
	def UserOnline 
	{
		id(type = String)
		userId(type = String)
		lasttime(type = String)
	}
}
```

生成内容

```java
public class User {
  private String id;
  private String name;
  private String address;
}

public class UserOnline {
  private String id;
  private String userId;
  private String lasttime;
}
```