<p class="title">ResearchableData<span> : <a href="https://docs.unity3d.com/6000.1/Documentation/ScriptReference/ScriptableObject.html" title="ScriptableObject" class="inherit-link">ScriptableObject</a></span><p>

## Fields

### id

A unique identifier for the researchable item. Suggested format is ModName.Name. IE:
		     "IndustrialValley.AdvancedConveyorBelt"

<div><Declaration modifier="public string" content=" <span>&lt;span class=&quot;field&quot;&gt;id&lt;/span&gt;</span>"></Declaration></div>

### name

<div><Declaration modifier="public new string" content=" <span>&lt;span class=&quot;field&quot;&gt;name&lt;/span&gt;</span>"></Declaration></div>

### description

<div><Declaration modifier="public string" content=" <span>&lt;span class=&quot;field&quot;&gt;description&lt;/span&gt;</span>"></Declaration></div>

### cost

<div><Declaration modifier="public int" content=" <span>&lt;span class=&quot;field&quot;&gt;cost&lt;/span&gt;</span>"></Declaration></div>

### timeToComplete

Time in seconds it takes to complete the research.

<div><Declaration modifier="public int" content=" <span>&lt;span class=&quot;field&quot;&gt;timeToComplete&lt;/span&gt;</span>"></Declaration></div>

### icon

<div><Declaration modifier="public &lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/Texture2D.html&quot; title=&quot;Texture2D&quot; class=&quot;inherit-link&quot;&gt;Texture2D&lt;/a&gt;" content=" <span>&lt;span class=&quot;field&quot;&gt;icon&lt;/span&gt;</span>"></Declaration></div>

### prerequisites

Research that must be completed before this one can be started.

<div><Declaration modifier="public List&amp;lt;&lt;a href=&quot;#/api/IndustrialValley.Data/ResearchableData&quot; title=&quot;ResearchableData&quot; class=&quot;inherit-link&quot;&gt;ResearchableData&lt;/a&gt;&amp;gt;" content=" <span>&lt;span class=&quot;field&quot;&gt;prerequisites&lt;/span&gt;</span>"></Declaration></div>

### buildablesUnlocked

<div><Declaration modifier="public List&amp;lt;&lt;a href=&quot;#/api/IndustrialValley.Data/BuildableData&quot; title=&quot;BuildableData&quot; class=&quot;inherit-link&quot;&gt;BuildableData&lt;/a&gt;&amp;gt;" content=" <span>&lt;span class=&quot;field&quot;&gt;buildablesUnlocked&lt;/span&gt;</span>"></Declaration></div>

### recipesUnlocked

<div><Declaration modifier="public List&amp;lt;&lt;a href=&quot;#/api/IndustrialValley.Data/RecipeData&quot; title=&quot;RecipeData&quot; class=&quot;inherit-link&quot;&gt;RecipeData&lt;/a&gt;&amp;gt;" content=" <span>&lt;span class=&quot;field&quot;&gt;recipesUnlocked&lt;/span&gt;</span>"></Declaration></div>

## Methods

### IsBuildableResearchable

Returns if the buildable is researchable.

<div><Declaration modifier="public bool" content=" <span>&lt;span class=&quot;method&quot;&gt;IsBuildableResearchable&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Data/BuildableData&quot; title=&quot;BuildableData&quot; class=&quot;inherit-link&quot;&gt;BuildableData&lt;/a&gt;&lt;/span&gt; buildable)</span>"></Declaration></div>

### IsRecipeResearchable

Returns if the recipe is researchable.

<div><Declaration modifier="public bool" content=" <span>&lt;span class=&quot;method&quot;&gt;IsRecipeResearchable&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Data/RecipeData&quot; title=&quot;RecipeData&quot; class=&quot;inherit-link&quot;&gt;RecipeData&lt;/a&gt;&lt;/span&gt; recipe)</span>"></Declaration></div>
