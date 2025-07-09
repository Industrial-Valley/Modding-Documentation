<p class="title">ColumnBuilder</p>

## Constructors


### ColumnBuilder

<div><Declaration modifier="public" content=" <span>&lt;span class=&quot;method&quot;&gt;ColumnBuilder&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; name)</span>"></Declaration></div>

## Properties


### Name
<div><Declaration modifier="public string" content=" <span>&lt;span class=&quot;property&quot;&gt;Name&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

### Type
<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/ColumnBuilder.ColumnType&quot; title=&quot;ColumnBuilder.ColumnType&quot; class=&quot;inherit-link&quot;&gt;ColumnType&lt;/a&gt;" content=" <span>&lt;span class=&quot;property&quot;&gt;Type&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

### IsNullable
<div><Declaration modifier="public bool" content=" <span>&lt;span class=&quot;property&quot;&gt;IsNullable&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

### DefaultValue
<div><Declaration modifier="public object" content=" <span>&lt;span class=&quot;property&quot;&gt;DefaultValue&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

### IsPrimaryKey
<div><Declaration modifier="public bool" content=" <span>&lt;span class=&quot;property&quot;&gt;IsPrimaryKey&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

### IsAutoIncrement
<div><Declaration modifier="public bool" content=" <span>&lt;span class=&quot;property&quot;&gt;IsAutoIncrement&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

## Methods

### New

Creates a new column with the specified name.

<div><Declaration modifier="public static &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/ColumnBuilder&quot; title=&quot;ColumnBuilder&quot; class=&quot;inherit-link&quot;&gt;ColumnBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;New&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; name)</span>"></Declaration></div>

### SetType

Sets the type of the column.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/ColumnBuilder&quot; title=&quot;ColumnBuilder&quot; class=&quot;inherit-link&quot;&gt;ColumnBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;SetType&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/ColumnBuilder.ColumnType&quot; title=&quot;ColumnBuilder.ColumnType&quot; class=&quot;inherit-link&quot;&gt;ColumnType&lt;/a&gt;&lt;/span&gt; type)</span>"></Declaration></div>

### AutoIncrement

Sets the column as an auto-incrementing primary key.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/ColumnBuilder&quot; title=&quot;ColumnBuilder&quot; class=&quot;inherit-link&quot;&gt;ColumnBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;AutoIncrement&lt;/span&gt;()</span>"></Declaration></div>

### SetNullable

Sets whether the column can be null.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/ColumnBuilder&quot; title=&quot;ColumnBuilder&quot; class=&quot;inherit-link&quot;&gt;ColumnBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;SetNullable&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;bool&lt;/span&gt; isNullable)</span>"></Declaration></div>

### SetDefaultValue

Sets the default value for the column.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/ColumnBuilder&quot; title=&quot;ColumnBuilder&quot; class=&quot;inherit-link&quot;&gt;ColumnBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;SetDefaultValue&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;object&lt;/span&gt; value)</span>"></Declaration></div>

### DateTime

Sets the column as a DateTime type with a default value of the current date.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/ColumnBuilder&quot; title=&quot;ColumnBuilder&quot; class=&quot;inherit-link&quot;&gt;ColumnBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;DateTime&lt;/span&gt;()</span>"></Declaration></div>

### SetIsPrimaryKey

Sets the column as a primary key.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/ColumnBuilder&quot; title=&quot;ColumnBuilder&quot; class=&quot;inherit-link&quot;&gt;ColumnBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;SetIsPrimaryKey&lt;/span&gt;()</span>"></Declaration></div>

### ToString

<div><Declaration modifier="public override string" content=" <span>&lt;span class=&quot;method&quot;&gt;ToString&lt;/span&gt;()</span>"></Declaration></div>
