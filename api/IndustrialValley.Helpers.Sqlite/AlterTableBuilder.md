<p class="title">AlterTableBuilder</p>

## Constructors


### AlterTableBuilder

<div><Declaration modifier="public" content=" <span>&lt;span class=&quot;method&quot;&gt;AlterTableBuilder&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; currentTable)</span>"></Declaration></div>

## Properties


### CurrentTable
<div><Declaration modifier="public string" content=" <span>&lt;span class=&quot;property&quot;&gt;CurrentTable&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; }</span>"></Declaration></div>

### NewColumn
<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/ColumnBuilder&quot; title=&quot;ColumnBuilder&quot; class=&quot;inherit-link&quot;&gt;ColumnBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;property&quot;&gt;NewColumn&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; }</span>"></Declaration></div>

### RenamedColumn
<div><Declaration modifier="public string" content=" <span>&lt;span class=&quot;property&quot;&gt;RenamedColumn&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; }</span>"></Declaration></div>

### RenameTableTo
<div><Declaration modifier="public string" content=" <span>&lt;span class=&quot;property&quot;&gt;RenameTableTo&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

## Methods

### New

Creates a new AlterTableBuilder for the specified table.

<div><Declaration modifier="public static &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/AlterTableBuilder&quot; title=&quot;AlterTableBuilder&quot; class=&quot;inherit-link&quot;&gt;AlterTableBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;New&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; currentTable)</span>"></Declaration></div>

### AddColumn

Adds a column to the table. Can't be used with other alterations in the same statement.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/AlterTableBuilder&quot; title=&quot;AlterTableBuilder&quot; class=&quot;inherit-link&quot;&gt;AlterTableBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;AddColumn&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/ColumnBuilder&quot; title=&quot;ColumnBuilder&quot; class=&quot;inherit-link&quot;&gt;ColumnBuilder&lt;/a&gt;&lt;/span&gt; column)</span>"></Declaration></div>

### RenameTable

Renames the table to a new name. Can't be used with other alterations in the same statement.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/AlterTableBuilder&quot; title=&quot;AlterTableBuilder&quot; class=&quot;inherit-link&quot;&gt;AlterTableBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;RenameTable&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; newName)</span>"></Declaration></div>

### RenameColumn

Renames a column in the table. Can't be used with other alterations in the same statement.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/AlterTableBuilder&quot; title=&quot;AlterTableBuilder&quot; class=&quot;inherit-link&quot;&gt;AlterTableBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;RenameColumn&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; oldName, &lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; newName)</span>"></Declaration></div>

### AddTextColumn

Adds a text column to the table. Text columns can store strings.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/AlterTableBuilder&quot; title=&quot;AlterTableBuilder&quot; class=&quot;inherit-link&quot;&gt;AlterTableBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;AddTextColumn&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; name, &lt;span class=&quot;param&quot;&gt;bool&lt;/span&gt; isNullable = true)</span>"></Declaration></div>

### AddIntegerColumn

Adds an integer column to the table. Integer columns can store whole numbers.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/AlterTableBuilder&quot; title=&quot;AlterTableBuilder&quot; class=&quot;inherit-link&quot;&gt;AlterTableBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;AddIntegerColumn&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; name, &lt;span class=&quot;param&quot;&gt;bool&lt;/span&gt; isNullable = true)</span>"></Declaration></div>

### AddRealColumn

Adds a real (floating point) column to the table. Real columns can store decimal values.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/AlterTableBuilder&quot; title=&quot;AlterTableBuilder&quot; class=&quot;inherit-link&quot;&gt;AlterTableBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;AddRealColumn&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; name, &lt;span class=&quot;param&quot;&gt;bool&lt;/span&gt; isNullable = true)</span>"></Declaration></div>

### AddNumericColumn

Adds a numeric column to the table. Numeric columns can store decimal values.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/AlterTableBuilder&quot; title=&quot;AlterTableBuilder&quot; class=&quot;inherit-link&quot;&gt;AlterTableBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;AddNumericColumn&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; name, &lt;span class=&quot;param&quot;&gt;bool&lt;/span&gt; isNullable = true)</span>"></Declaration></div>

### ToString

<div><Declaration modifier="public override string" content=" <span>&lt;span class=&quot;method&quot;&gt;ToString&lt;/span&gt;()</span>"></Declaration></div>
