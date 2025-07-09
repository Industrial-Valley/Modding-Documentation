<p class="title">DeleteBuilder</p>

## Constructors


### DeleteBuilder

<div><Declaration modifier="public" content=" <span>&lt;span class=&quot;method&quot;&gt;DeleteBuilder&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; tableName)</span>"></Declaration></div>

## Properties


### TableName
<div><Declaration modifier="public string" content=" <span>&lt;span class=&quot;property&quot;&gt;TableName&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

### WhereBuilder
<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder&quot; title=&quot;WhereBuilder&quot; class=&quot;inherit-link&quot;&gt;WhereBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;property&quot;&gt;WhereBuilder&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

### CanDeleteAll
<div><Declaration modifier="public bool" content=" <span>&lt;span class=&quot;property&quot;&gt;CanDeleteAll&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

### Limit
<div><Declaration modifier="public int" content=" <span>&lt;span class=&quot;property&quot;&gt;Limit&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

### Offset
<div><Declaration modifier="public int" content=" <span>&lt;span class=&quot;property&quot;&gt;Offset&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

## Methods

### New

Creates a new instance of DeleteBuilder with the specified table name.

<div><Declaration modifier="public static &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/DeleteBuilder&quot; title=&quot;DeleteBuilder&quot; class=&quot;inherit-link&quot;&gt;DeleteBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;New&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; tableName)</span>"></Declaration></div>

### Where

Where clause for filtering results.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/DeleteBuilder&quot; title=&quot;DeleteBuilder&quot; class=&quot;inherit-link&quot;&gt;DeleteBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;Where&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder&quot; title=&quot;WhereBuilder&quot; class=&quot;inherit-link&quot;&gt;WhereBuilder&lt;/a&gt;&lt;/span&gt; where)</span>"></Declaration></div>

### Where

Adds a where clause to the select statement with a specific column, operator, and value.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/DeleteBuilder&quot; title=&quot;DeleteBuilder&quot; class=&quot;inherit-link&quot;&gt;DeleteBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;Where&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; column, &lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder.WhereOperator&quot; title=&quot;WhereBuilder.WhereOperator&quot; class=&quot;inherit-link&quot;&gt;WhereOperator&lt;/a&gt;&lt;/span&gt; @operator, &lt;span class=&quot;param&quot;&gt;object&lt;/span&gt; value)</span>"></Declaration></div>

### AllowDeleteAll

This method allows the deletion of all records from the table without a WHERE clause.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/DeleteBuilder&quot; title=&quot;DeleteBuilder&quot; class=&quot;inherit-link&quot;&gt;DeleteBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;AllowDeleteAll&lt;/span&gt;()</span>"></Declaration></div>

### SetLimit

Sets the limit for the number of rows returned by the query.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/DeleteBuilder&quot; title=&quot;DeleteBuilder&quot; class=&quot;inherit-link&quot;&gt;DeleteBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;SetLimit&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;int&lt;/span&gt; limit)</span>"></Declaration></div>

### SetOffset

Sets the offset for the query, which is used for pagination.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/DeleteBuilder&quot; title=&quot;DeleteBuilder&quot; class=&quot;inherit-link&quot;&gt;DeleteBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;SetOffset&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;int&lt;/span&gt; offset)</span>"></Declaration></div>

### ToString

<div><Declaration modifier="public override string" content=" <span>&lt;span class=&quot;method&quot;&gt;ToString&lt;/span&gt;()</span>"></Declaration></div>
