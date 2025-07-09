<p class="title">UpdateBuilder</p>

## Constructors


### UpdateBuilder

<div><Declaration modifier="public" content=" <span>&lt;span class=&quot;method&quot;&gt;UpdateBuilder&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; tableName)</span>"></Declaration></div>

## Properties


### TableName
<div><Declaration modifier="public string" content=" <span>&lt;span class=&quot;property&quot;&gt;TableName&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

### Data
<div><Declaration modifier="public Dictionary&amp;lt;string, System.Object&amp;gt;" content=" <span>&lt;span class=&quot;property&quot;&gt;Data&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; }</span>"></Declaration></div>

### WhereBuilder
<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder&quot; title=&quot;WhereBuilder&quot; class=&quot;inherit-link&quot;&gt;WhereBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;property&quot;&gt;WhereBuilder&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

### Limit
<div><Declaration modifier="public int" content=" <span>&lt;span class=&quot;property&quot;&gt;Limit&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

### Offset
<div><Declaration modifier="public int" content=" <span>&lt;span class=&quot;property&quot;&gt;Offset&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

### UpdateAllAllowed
<div><Declaration modifier="public bool" content=" <span>&lt;span class=&quot;property&quot;&gt;UpdateAllAllowed&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

## Methods

### New

Creates a new instance of InsertBuilder with the specified table name.

<div><Declaration modifier="public static &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/UpdateBuilder&quot; title=&quot;UpdateBuilder&quot; class=&quot;inherit-link&quot;&gt;UpdateBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;New&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; tableName)</span>"></Declaration></div>

### Set

Adds a column and value to the insert statement.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/UpdateBuilder&quot; title=&quot;UpdateBuilder&quot; class=&quot;inherit-link&quot;&gt;UpdateBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;Set&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; column, &lt;span class=&quot;param&quot;&gt;object&lt;/span&gt; value)</span>"></Declaration></div>

### Where

Where clause for filtering results.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/UpdateBuilder&quot; title=&quot;UpdateBuilder&quot; class=&quot;inherit-link&quot;&gt;UpdateBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;Where&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder&quot; title=&quot;WhereBuilder&quot; class=&quot;inherit-link&quot;&gt;WhereBuilder&lt;/a&gt;&lt;/span&gt; where)</span>"></Declaration></div>

### Where

Adds a where clause to the select statement with a specific column, operator, and value.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/UpdateBuilder&quot; title=&quot;UpdateBuilder&quot; class=&quot;inherit-link&quot;&gt;UpdateBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;Where&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; column, &lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder.WhereOperator&quot; title=&quot;WhereBuilder.WhereOperator&quot; class=&quot;inherit-link&quot;&gt;WhereOperator&lt;/a&gt;&lt;/span&gt; @operator, &lt;span class=&quot;param&quot;&gt;object&lt;/span&gt; value)</span>"></Declaration></div>

### SetLimit

This will limit the update to only set amount of records.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/UpdateBuilder&quot; title=&quot;UpdateBuilder&quot; class=&quot;inherit-link&quot;&gt;UpdateBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;SetLimit&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;int&lt;/span&gt; limit)</span>"></Declaration></div>

### SetOffset

Sets the offset for the update operation.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/UpdateBuilder&quot; title=&quot;UpdateBuilder&quot; class=&quot;inherit-link&quot;&gt;UpdateBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;SetOffset&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;int&lt;/span&gt; offset)</span>"></Declaration></div>

### AllowUpdateAll

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/UpdateBuilder&quot; title=&quot;UpdateBuilder&quot; class=&quot;inherit-link&quot;&gt;UpdateBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;AllowUpdateAll&lt;/span&gt;()</span>"></Declaration></div>

### ToString

<div><Declaration modifier="public override string" content=" <span>&lt;span class=&quot;method&quot;&gt;ToString&lt;/span&gt;()</span>"></Declaration></div>
