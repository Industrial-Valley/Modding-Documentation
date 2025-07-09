<p class="title">WhereBuilder</p>

## Constructors


### WhereBuilder

<div><Declaration modifier="public" content=" <span>&lt;span class=&quot;method&quot;&gt;WhereBuilder&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; column, &lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder.WhereOperator&quot; title=&quot;WhereBuilder.WhereOperator&quot; class=&quot;inherit-link&quot;&gt;WhereOperator&lt;/a&gt;&lt;/span&gt; @operator, &lt;span class=&quot;param&quot;&gt;object&lt;/span&gt; value)</span>"></Declaration></div>

## Properties


### Column
<div><Declaration modifier="public string" content=" <span>&lt;span class=&quot;property&quot;&gt;Column&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

### Operator
<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder.WhereOperator&quot; title=&quot;WhereBuilder.WhereOperator&quot; class=&quot;inherit-link&quot;&gt;WhereOperator&lt;/a&gt;" content=" <span>&lt;span class=&quot;property&quot;&gt;Operator&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

### Value
<div><Declaration modifier="public object" content=" <span>&lt;span class=&quot;property&quot;&gt;Value&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

### OrConditions
<div><Declaration modifier="public List&amp;lt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder&quot; title=&quot;WhereBuilder&quot; class=&quot;inherit-link&quot;&gt;WhereBuilder&lt;/a&gt;&amp;gt;" content=" <span>&lt;span class=&quot;property&quot;&gt;OrConditions&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; }</span>"></Declaration></div>

### AndConditions
<div><Declaration modifier="public List&amp;lt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder&quot; title=&quot;WhereBuilder&quot; class=&quot;inherit-link&quot;&gt;WhereBuilder&lt;/a&gt;&amp;gt;" content=" <span>&lt;span class=&quot;property&quot;&gt;AndConditions&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; }</span>"></Declaration></div>

### OrderByDirections
<div><Declaration modifier="public Dictionary&amp;lt;string, IndustrialValley.Helpers.Sqlite.WhereBuilder.OrderByDirection&amp;gt;" content=" <span>&lt;span class=&quot;property&quot;&gt;OrderByDirections&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; }</span>"></Declaration></div>

## Methods

### New

Creates a new instance of WhereBuilder with the specified column, operator, and value.

<div><Declaration modifier="public static &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder&quot; title=&quot;WhereBuilder&quot; class=&quot;inherit-link&quot;&gt;WhereBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;New&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; column, &lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder.WhereOperator&quot; title=&quot;WhereBuilder.WhereOperator&quot; class=&quot;inherit-link&quot;&gt;WhereOperator&lt;/a&gt;&lt;/span&gt; @operator, &lt;span class=&quot;param&quot;&gt;object&lt;/span&gt; value = null)</span>"></Declaration></div>

### Or

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder&quot; title=&quot;WhereBuilder&quot; class=&quot;inherit-link&quot;&gt;WhereBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;Or&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; column, &lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder.WhereOperator&quot; title=&quot;WhereBuilder.WhereOperator&quot; class=&quot;inherit-link&quot;&gt;WhereOperator&lt;/a&gt;&lt;/span&gt; @operator, &lt;span class=&quot;param&quot;&gt;object&lt;/span&gt; value)</span>"></Declaration></div>

### And

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder&quot; title=&quot;WhereBuilder&quot; class=&quot;inherit-link&quot;&gt;WhereBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;And&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; column, &lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder.WhereOperator&quot; title=&quot;WhereBuilder.WhereOperator&quot; class=&quot;inherit-link&quot;&gt;WhereOperator&lt;/a&gt;&lt;/span&gt; @operator, &lt;span class=&quot;param&quot;&gt;object&lt;/span&gt; value)</span>"></Declaration></div>

### OrderBy

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder&quot; title=&quot;WhereBuilder&quot; class=&quot;inherit-link&quot;&gt;WhereBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;OrderBy&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; column, &lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/WhereBuilder.OrderByDirection&quot; title=&quot;WhereBuilder.OrderByDirection&quot; class=&quot;inherit-link&quot;&gt;OrderByDirection&lt;/a&gt;&lt;/span&gt; direction = OrderByDirection.Ascending)</span>"></Declaration></div>

### ToString

<div><Declaration modifier="public override string" content=" <span>&lt;span class=&quot;method&quot;&gt;ToString&lt;/span&gt;()</span>"></Declaration></div>
