<p class="title">InsertBuilder</p>

## Constructors


### InsertBuilder

<div><Declaration modifier="public" content=" <span>&lt;span class=&quot;method&quot;&gt;InsertBuilder&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; tableName)</span>"></Declaration></div>

## Properties


### TableName
<div><Declaration modifier="public string" content=" <span>&lt;span class=&quot;property&quot;&gt;TableName&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

### OrReplace
<div><Declaration modifier="public bool" content=" <span>&lt;span class=&quot;property&quot;&gt;OrReplace&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

### Data
<div><Declaration modifier="public Dictionary&amp;lt;string, System.Object&amp;gt;" content=" <span>&lt;span class=&quot;property&quot;&gt;Data&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; }</span>"></Declaration></div>

## Methods

### New

Creates a new instance of InsertBuilder with the specified table name.

<div><Declaration modifier="public static &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/InsertBuilder&quot; title=&quot;InsertBuilder&quot; class=&quot;inherit-link&quot;&gt;InsertBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;New&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; tableName)</span>"></Declaration></div>

### Set

Adds a column and value to the insert statement.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/InsertBuilder&quot; title=&quot;InsertBuilder&quot; class=&quot;inherit-link&quot;&gt;InsertBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;Set&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; column, &lt;span class=&quot;param&quot;&gt;object&lt;/span&gt; value)</span>"></Declaration></div>

### ReplaceExisting

This method allows the insertion to replace existing records with the same primary key.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers.Sqlite/InsertBuilder&quot; title=&quot;InsertBuilder&quot; class=&quot;inherit-link&quot;&gt;InsertBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;ReplaceExisting&lt;/span&gt;()</span>"></Declaration></div>

### ToString

<div><Declaration modifier="public override string" content=" <span>&lt;span class=&quot;method&quot;&gt;ToString&lt;/span&gt;()</span>"></Declaration></div>
