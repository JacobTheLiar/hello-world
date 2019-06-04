# hello-world

My name is Jakub. It is
the first edition of data on GitHub, a test site mainly related to the .md file.

I'm learning from the tutorial posted [here](https://agea.github.io/tutorial.md).

***
## list example
1. with `*`
* one
* two
* three

2. with `-`
- do
- while

3. with `+`
+ begin
+ end

***
## example code

1) inline `unit DataExport;`

2) fenced delphi ` ``` `
```delphi
function TFileVersion.GetBulidNumber: Integer;
begin
  Result := FBuild
end;
```
3) fenced java `~~~`
~~~java
public interface StorageOrder {

    List<Order> getOrderList();
    Order getOrder(int orderNumber);
    void deleteOrder(int orderNumber);
    void addOrder(Order order);
    int getOrderCount();
}
~~~

4) some SQL with ` ``` `
```sql
create procedure [dbo].[registerEvent](
  @userId int
  @operation varchar(250),
) as

  insert into log (operaton, userId, eventTime)
    values (@operation, @userId, getDate())

  exec dbo.admExecutedProcedure @aProcID = @@PROCID
```
***
## some pictures
![image1](http://agea.github.io/tutorial.md/img/1.png)
![image2](http://agea.github.io/tutorial.md/img/2.png)
***
end of file.
