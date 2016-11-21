```
var db = Database.Open("StarterSite");
    var sql = "CREATE TABLE [test] " +
                "(Id int IDENTITY NOT NULL PRIMARY KEY, " +
                "NAME NVARCHAR(50), " +
                "DATE DATETIME)";
    db.Execute(sql);
    ```
