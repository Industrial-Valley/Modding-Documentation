<p class="title">TableBuilder</p>

## Constructors


### TableBuilder

<div><Declaration modifier="public" content=" <span>&lt;span class=&quot;method&quot;&gt;TableBuilder&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; name)</span>"></Declaration></div>

## Properties


### Name
<div><Declaration modifier="public string" content=" <span>&lt;span class=&quot;property&quot;&gt;Name&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

### Columns
<div><Declaration modifier="public List&amp;lt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/ColumnBuilder&quot; title=&quot;ColumnBuilder&quot; class=&quot;inherit-link&quot;&gt;ColumnBuilder&lt;/a&gt;&amp;gt;" content=" <span>&lt;span class=&quot;property&quot;&gt;Columns&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; }</span>"></Declaration></div>

## Methods

### AddColumn

Adds a column to the table.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/TableBuilder&quot; title=&quot;TableBuilder&quot; class=&quot;inherit-link&quot;&gt;TableBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;AddColumn&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/ColumnBuilder&quot; title=&quot;ColumnBuilder&quot; class=&quot;inherit-link&quot;&gt;ColumnBuilder&lt;/a&gt;&lt;/span&gt; column)</span>"></Declaration></div>

### New

<div><Declaration modifier="public static &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/TableBuilder&quot; title=&quot;TableBuilder&quot; class=&quot;inherit-link&quot;&gt;TableBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;New&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; name)</span>"></Declaration></div>

### Text

Creates a text column.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/TableBuilder&quot; title=&quot;TableBuilder&quot; class=&quot;inherit-link&quot;&gt;TableBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;Text&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; name)</span>"></Declaration></div>

### Integer

Creates an integer column.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/TableBuilder&quot; title=&quot;TableBuilder&quot; class=&quot;inherit-link&quot;&gt;TableBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;Integer&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; name, &lt;span class=&quot;param&quot;&gt;long&lt;/span&gt; defaultValue = 0)</span>"></Declaration></div>

### Real

Creates a real number column.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/TableBuilder&quot; title=&quot;TableBuilder&quot; class=&quot;inherit-link&quot;&gt;TableBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;Real&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; name, &lt;span class=&quot;param&quot;&gt;float&lt;/span&gt; defaultValue = 0.0f)</span>"></Declaration></div>

### Numeric

Creates a numeric column.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/TableBuilder&quot; title=&quot;TableBuilder&quot; class=&quot;inherit-link&quot;&gt;TableBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;Numeric&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; name)</span>"></Declaration></div>

### Date

Adds a date column with the default value set to the current date.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/TableBuilder&quot; title=&quot;TableBuilder&quot; class=&quot;inherit-link&quot;&gt;TableBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;Date&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; name)</span>"></Declaration></div>

### AutoIncrement

Adds an auto-incrementing column.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/TableBuilder&quot; title=&quot;TableBuilder&quot; class=&quot;inherit-link&quot;&gt;TableBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;AutoIncrement&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; name)</span>"></Declaration></div>

### Id

Adds an auto-incrementing primary key column named "id".

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/TableBuilder&quot; title=&quot;TableBuilder&quot; class=&quot;inherit-link&quot;&gt;TableBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;Id&lt;/span&gt;()</span>"></Declaration></div>

### AddBoolColumn

Adds a boolean column with a default value.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/TableBuilder&quot; title=&quot;TableBuilder&quot; class=&quot;inherit-link&quot;&gt;TableBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;AddBoolColumn&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; name, &lt;span class=&quot;param&quot;&gt;bool&lt;/span&gt; defaultValue = false)</span>"></Declaration></div>

### ToString

<div><Declaration modifier="public override string" content=" <span>&lt;span class=&quot;method&quot;&gt;ToString&lt;/span&gt;()</span>"></Declaration></div>
