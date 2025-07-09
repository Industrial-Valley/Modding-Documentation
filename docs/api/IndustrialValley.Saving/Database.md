<p class="title">Database</p>

## Methods

### AddMigration

Adds a migration to the database. The migration will only run once.

<div><Declaration modifier="public static void" content=" <span>&lt;span class=&quot;method&quot;&gt;AddMigration&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/Migration&quot; title=&quot;Migration&quot; class=&quot;inherit-link&quot;&gt;Migration&lt;/a&gt;&lt;/span&gt; migration)</span>"></Declaration></div>

### RawSql

Executes a raw SQL command that does not return any results (e.g., INSERT, UPDATE, DELETE).

<div><Declaration modifier="public static long" content=" <span>&lt;span class=&quot;method&quot;&gt;RawSql&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; sql)</span>"></Declaration></div>

### RawSqlWithResult

Executes a raw SQL command that returns results.

<div><Declaration modifier="public static IndustrialValley.Saving.SqlResult&amp;lt;T&amp;gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;RawSqlWithResult&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; sql)</span>"></Declaration></div>

### Delete

Deletes a record from the database using the provided DeleteBuilder.

<div><Declaration modifier="public static void" content=" <span>&lt;span class=&quot;method&quot;&gt;Delete&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/DeleteBuilder&quot; title=&quot;DeleteBuilder&quot; class=&quot;inherit-link&quot;&gt;DeleteBuilder&lt;/a&gt;&lt;/span&gt; builder)</span>"></Declaration></div>

### Delete

Deletes a record from the database for the specified item.

<div><Declaration modifier="public static void" content=" <span>&lt;span class=&quot;method&quot;&gt;Delete&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder&quot; title=&quot;WhereBuilder&quot; class=&quot;inherit-link&quot;&gt;WhereBuilder&lt;/a&gt;&lt;/span&gt; where)</span>"></Declaration></div>

### DeleteById

Deletes an existing record in the database by its id column.

<div><Declaration modifier="public static void" content=" <span>&lt;span class=&quot;method&quot;&gt;DeleteById&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;long&lt;/span&gt; id)</span>"></Declaration></div>

### Insert

Inserts a new record into the database using the provided InsertBuilder.

<div><Declaration modifier="public static long" content=" <span>&lt;span class=&quot;method&quot;&gt;Insert&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/InsertBuilder&quot; title=&quot;InsertBuilder&quot; class=&quot;inherit-link&quot;&gt;InsertBuilder&lt;/a&gt;&lt;/span&gt; builder)</span>"></Declaration></div>

### Insert

Inserts a new record into the database for the specified item.

<div><Declaration modifier="public static long" content=" <span>&lt;span class=&quot;method&quot;&gt;Insert&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;T&lt;/span&gt; item)</span>"></Declaration></div>

### Replace

Inserts a new record into the database, replacing any existing record with the same primary key.

<div><Declaration modifier="public static long" content=" <span>&lt;span class=&quot;method&quot;&gt;Replace&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/InsertBuilder&quot; title=&quot;InsertBuilder&quot; class=&quot;inherit-link&quot;&gt;InsertBuilder&lt;/a&gt;&lt;/span&gt; builder)</span>"></Declaration></div>

### Replace

Inserts a new record into the database, replacing any existing record with the same primary key.

<div><Declaration modifier="public static long" content=" <span>&lt;span class=&quot;method&quot;&gt;Replace&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;T&lt;/span&gt; item)</span>"></Declaration></div>

### SelectAll

Selects all records from the specified table and returns them as a list of type T.

<div><Declaration modifier="public static IndustrialValley.Saving.SqlResult&amp;lt;T&amp;gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;SelectAll&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/SelectBuilder&quot; title=&quot;SelectBuilder&quot; class=&quot;inherit-link&quot;&gt;SelectBuilder&lt;/a&gt;&lt;/span&gt; builder)</span>"></Declaration></div>

### SelectAll

Selects all records from the specified table and returns them as a list of type T.

<div><Declaration modifier="public static IndustrialValley.Saving.SqlResult&amp;lt;T&amp;gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;SelectAll&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder&quot; title=&quot;WhereBuilder&quot; class=&quot;inherit-link&quot;&gt;WhereBuilder&lt;/a&gt;&lt;/span&gt; where = null, &lt;span class=&quot;param&quot;&gt;List&amp;amp;lt;string&amp;amp;gt;&lt;/span&gt; columns = null)</span>"></Declaration></div>

### Select

Selects a single record from the specified table and returns it as an instance of type T.

<div><Declaration modifier="public static T" content=" <span>&lt;span class=&quot;method&quot;&gt;Select&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/SelectBuilder&quot; title=&quot;SelectBuilder&quot; class=&quot;inherit-link&quot;&gt;SelectBuilder&lt;/a&gt;&lt;/span&gt; builder)</span>"></Declaration></div>

### Select

Selects a single record from the specified table and returns it as an instance of type T.

<div><Declaration modifier="public static T" content=" <span>&lt;span class=&quot;method&quot;&gt;Select&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; tableName = &quot;&quot;, &lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder&quot; title=&quot;WhereBuilder&quot; class=&quot;inherit-link&quot;&gt;WhereBuilder&lt;/a&gt;&lt;/span&gt; where = null, &lt;span class=&quot;param&quot;&gt;List&amp;amp;lt;string&amp;amp;gt;&lt;/span&gt; columns = null)</span>"></Declaration></div>

### AddTable

Adds a new table to the database using the provided TableBuilder.

<div><Declaration modifier="public static void" content=" <span>&lt;span class=&quot;method&quot;&gt;AddTable&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/TableBuilder&quot; title=&quot;TableBuilder&quot; class=&quot;inherit-link&quot;&gt;TableBuilder&lt;/a&gt;&lt;/span&gt; builder)</span>"></Declaration></div>

### AddTable

Adds a new table to the database based on the provided type T, can be used to customize the table

<div><Declaration modifier="public static void" content=" <span>&lt;span class=&quot;method&quot;&gt;AddTable&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;IndustrialValley.Helpers.Sqlite.TableBuilder System.Func&amp;amp;lt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/.TableBuilder&quot; title=&quot;.TableBuilder&quot; class=&quot;inherit-link&quot;&gt;TableBuilder&lt;/a&gt;&amp;amp;gt;&lt;/span&gt; builderFunc)</span>"></Declaration></div>

### AddTable

Adds a new table to the database based on the provided type T.

<div><Declaration modifier="public static void" content=" <span>&lt;span class=&quot;method&quot;&gt;AddTable&lt;/span&gt;()</span>"></Declaration></div>

### AlterTable

<div><Declaration modifier="public static void" content=" <span>&lt;span class=&quot;method&quot;&gt;AlterTable&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/AlterTableBuilder&quot; title=&quot;AlterTableBuilder&quot; class=&quot;inherit-link&quot;&gt;AlterTableBuilder&lt;/a&gt;&lt;/span&gt; builder)</span>"></Declaration></div>

### Update

Updates an existing record in the database using the provided InsertBuilder.

<div><Declaration modifier="public static void" content=" <span>&lt;span class=&quot;method&quot;&gt;Update&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/UpdateBuilder&quot; title=&quot;UpdateBuilder&quot; class=&quot;inherit-link&quot;&gt;UpdateBuilder&lt;/a&gt;&lt;/span&gt; builder)</span>"></Declaration></div>

### Update

Updates an existing record in the database for the specified item.

<div><Declaration modifier="public static void" content=" <span>&lt;span class=&quot;method&quot;&gt;Update&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;T&lt;/span&gt; item, &lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder&quot; title=&quot;WhereBuilder&quot; class=&quot;inherit-link&quot;&gt;WhereBuilder&lt;/a&gt;&lt;/span&gt; where)</span>"></Declaration></div>

### UpdateById

Updates an existing record in the database by its id column.

<div><Declaration modifier="public static void" content=" <span>&lt;span class=&quot;method&quot;&gt;UpdateById&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;long&lt;/span&gt; id, &lt;span class=&quot;param&quot;&gt;T&lt;/span&gt; item)</span>"></Declaration></div>
