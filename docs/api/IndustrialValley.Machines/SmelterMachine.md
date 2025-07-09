<p class="title">SmelterMachine<span> : <a href="#/api/IndustrialValley.Machines/RecipeMachine" title="RecipeMachine" class="inherit-link">RecipeMachine</a></span><p>

## Properties


### IsCrafting
<div><Declaration modifier="public bool" content=" <span>&lt;span class=&quot;property&quot;&gt;IsCrafting&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; }</span>"></Declaration></div>

### CraftingProgress
<div><Declaration modifier="public float" content=" <span>&lt;span class=&quot;property&quot;&gt;CraftingProgress&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; }</span>"></Declaration></div>

### CraftingProgressStyleLength
<div><Declaration modifier="public &lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/UIElements.StyleLength.html&quot; title=&quot;StyleLength&quot; class=&quot;inherit-link&quot;&gt;StyleLength&lt;/a&gt;" content=" <span>&lt;span class=&quot;property&quot;&gt;CraftingProgressStyleLength&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; }</span>"></Declaration></div>

### CraftingProgressText
<div><Declaration modifier="public string" content=" <span>&lt;span class=&quot;property&quot;&gt;CraftingProgressText&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; }</span>"></Declaration></div>

### RecipeName
<div><Declaration modifier="public string" content=" <span>&lt;span class=&quot;property&quot;&gt;RecipeName&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; }</span>"></Declaration></div>

### AssemblyTime
<div><Declaration modifier="public string" content=" <span>&lt;span class=&quot;property&quot;&gt;AssemblyTime&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; }</span>"></Declaration></div>

### CurrentRecipe
<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Data/RecipeData&quot; title=&quot;RecipeData&quot; class=&quot;inherit-link&quot;&gt;RecipeData&lt;/a&gt;" content=" <span>&lt;span class=&quot;property&quot;&gt;CurrentRecipe&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

### Recipes
<div><Declaration modifier="public Dictionary&amp;lt;&lt;a href=&quot;#/api/IndustrialValley.Data/.RecipeData&quot; title=&quot;.RecipeData&quot; class=&quot;inherit-link&quot;&gt;RecipeData&lt;/a&gt;&amp;gt;" content=" <span>&lt;span class=&quot;property&quot;&gt;Recipes&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

## Fields

### smokeEffect

<div><Declaration modifier="public &lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/ParticleSystem.html&quot; title=&quot;ParticleSystem&quot; class=&quot;inherit-link&quot;&gt;ParticleSystem&lt;/a&gt;" content=" <span>&lt;span class=&quot;field&quot;&gt;smokeEffect&lt;/span&gt;</span>"></Declaration></div>

### recipeType

<div><Declaration modifier="public IndustrialValley.Data.RecipeData.RecipeType" content=" <span>&lt;span class=&quot;field&quot;&gt;recipeType&lt;/span&gt;</span>"></Declaration></div>

### InputInventory

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Machines/Inventory&quot; title=&quot;Inventory&quot; class=&quot;inherit-link&quot;&gt;Inventory&lt;/a&gt;" content=" <span>&lt;span class=&quot;field&quot;&gt;InputInventory&lt;/span&gt;</span>"></Declaration></div>

### OutputInventory

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Machines/Inventory&quot; title=&quot;Inventory&quot; class=&quot;inherit-link&quot;&gt;Inventory&lt;/a&gt;" content=" <span>&lt;span class=&quot;field&quot;&gt;OutputInventory&lt;/span&gt;</span>"></Declaration></div>

### handoffDetectRadius

<div><Declaration modifier="public float" content=" <span>&lt;span class=&quot;field&quot;&gt;handoffDetectRadius&lt;/span&gt;</span>"></Declaration></div>

### handoffOffsets

<div><Declaration modifier="public UnityEngine.Vector3[]" content=" <span>&lt;span class=&quot;field&quot;&gt;handoffOffsets&lt;/span&gt;</span>"></Declaration></div>

### inputDetectRadius

<div><Declaration modifier="public float" content=" <span>&lt;span class=&quot;field&quot;&gt;inputDetectRadius&lt;/span&gt;</span>"></Declaration></div>

### inputOffsets

<div><Declaration modifier="public UnityEngine.Vector3[]" content=" <span>&lt;span class=&quot;field&quot;&gt;inputOffsets&lt;/span&gt;</span>"></Declaration></div>

### outputSpeed

<div><Declaration modifier="public float" content=" <span>&lt;span class=&quot;field&quot;&gt;outputSpeed&lt;/span&gt;</span>"></Declaration></div>

### lastOutputTime

<div><Declaration modifier="protected float" content=" <span>&lt;span class=&quot;field&quot;&gt;lastOutputTime&lt;/span&gt;</span>"></Declaration></div>

## Methods

### OnUpdate

<div><Declaration modifier="protected override void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnUpdate&lt;/span&gt;()</span>"></Declaration></div>

### OnSave

<div><Declaration modifier="public override &lt;a href=&quot;#/api/IndustrialValley.Saving/SaveableData&quot; title=&quot;SaveableData&quot; class=&quot;inherit-link&quot;&gt;SaveableData&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;OnSave&lt;/span&gt;()</span>"></Declaration></div>

### OnLoad

<div><Declaration modifier="public override void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnLoad&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Saving/SaveableData&quot; title=&quot;SaveableData&quot; class=&quot;inherit-link&quot;&gt;SaveableData&lt;/a&gt;&lt;/span&gt; data)</span>"></Declaration></div>

### CraftItem

<div><Declaration modifier="protected virtual System.Collections.IEnumerator" content=" <span>&lt;span class=&quot;method&quot;&gt;CraftItem&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;float&lt;/span&gt; overrideTime = 0f)</span>"></Declaration></div>

### CanAcceptItem

<div><Declaration modifier="public override bool" content=" <span>&lt;span class=&quot;method&quot;&gt;CanAcceptItem&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Conveyors/ConveyorItem&quot; title=&quot;ConveyorItem&quot; class=&quot;inherit-link&quot;&gt;ConveyorItem&lt;/a&gt;&lt;/span&gt; item)</span>"></Declaration></div>

### OnItemInserted

<div><Declaration modifier="protected override void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnItemInserted&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Conveyors/ConveyorItem&quot; title=&quot;ConveyorItem&quot; class=&quot;inherit-link&quot;&gt;ConveyorItem&lt;/a&gt;&lt;/span&gt; item)</span>"></Declaration></div>

### InsertItem

<div><Declaration modifier="public void" content=" <span>&lt;span class=&quot;method&quot;&gt;InsertItem&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Conveyors/ConveyorItem&quot; title=&quot;ConveyorItem&quot; class=&quot;inherit-link&quot;&gt;ConveyorItem&lt;/a&gt;&lt;/span&gt; item)</span>"></Declaration></div>

### GetInputPositions

Returns all world-space “green” input positions:
		     • transform.position + each inputOffset
		     • AND the splitter’s own center (transform.position)

<div><Declaration modifier="public List&amp;lt;&lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/Vector3.html&quot; title=&quot;Vector3&quot; class=&quot;inherit-link&quot;&gt;Vector3&lt;/a&gt;&amp;gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;GetInputPositions&lt;/span&gt;()</span>"></Declaration></div>

### GetOutputPositions

Returns all world-space “red” output positions:
		     • transform.position + each handoffOffset
		     • AND the splitter’s own center (transform.position)

<div><Declaration modifier="public List&amp;lt;&lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/Vector3.html&quot; title=&quot;Vector3&quot; class=&quot;inherit-link&quot;&gt;Vector3&lt;/a&gt;&amp;gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;GetOutputPositions&lt;/span&gt;()</span>"></Declaration></div>

### FindClosestDownstreamConveyor

Round‐robin through each output gizmo + center:
		     1) Tries OverlapSphere at each position.
		     2) If that finds none, tries distance-based fallback from that position.
		     Advances nextOutputIndex whenever a handoff is successful.

<div><Declaration modifier="protected &lt;a href=&quot;#/api/IndustrialValley.Conveyors/IConveyor&quot; title=&quot;IConveyor&quot; class=&quot;inherit-link&quot;&gt;IConveyor&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;FindClosestDownstreamConveyor&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Conveyors/ConveyorItem&quot; title=&quot;ConveyorItem&quot; class=&quot;inherit-link&quot;&gt;ConveyorItem&lt;/a&gt;&lt;/span&gt; item)</span>"></Declaration></div>

### OutputItem

<div><Declaration modifier="protected virtual bool" content=" <span>&lt;span class=&quot;method&quot;&gt;OutputItem&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Conveyors/ConveyorItem&quot; title=&quot;ConveyorItem&quot; class=&quot;inherit-link&quot;&gt;ConveyorItem&lt;/a&gt;&lt;/span&gt; item)</span>"></Declaration></div>
