<p class="title">Conveyor<span> : <a href="#/api/IndustrialValley.Conveyors/BaseMovement" title="BaseMovement" class="inherit-link">BaseMovement</a>, <a href="#/api/IndustrialValley.Conveyors/IConveyor" title="IConveyor" class="inherit-link">IConveyor</a></span><p>

## Fields

### startPoint

<div><Declaration modifier="public &lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/Transform.html&quot; title=&quot;Transform&quot; class=&quot;inherit-link&quot;&gt;Transform&lt;/a&gt;" content=" <span>&lt;span class=&quot;field&quot;&gt;startPoint&lt;/span&gt;</span>"></Declaration></div>

### controlPoint

<div><Declaration modifier="public &lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/Transform.html&quot; title=&quot;Transform&quot; class=&quot;inherit-link&quot;&gt;Transform&lt;/a&gt;" content=" <span>&lt;span class=&quot;field&quot;&gt;controlPoint&lt;/span&gt;</span>"></Declaration></div>

### endPoint

<div><Declaration modifier="public &lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/Transform.html&quot; title=&quot;Transform&quot; class=&quot;inherit-link&quot;&gt;Transform&lt;/a&gt;" content=" <span>&lt;span class=&quot;field&quot;&gt;endPoint&lt;/span&gt;</span>"></Declaration></div>

### moveSpeed

<div><Declaration modifier="public float" content=" <span>&lt;span class=&quot;field&quot;&gt;moveSpeed&lt;/span&gt;</span>"></Declaration></div>

### maxCapacity

<div><Declaration modifier="public int" content=" <span>&lt;span class=&quot;field&quot;&gt;maxCapacity&lt;/span&gt;</span>"></Declaration></div>

### minSpacing

<div><Declaration modifier="public float" content=" <span>&lt;span class=&quot;field&quot;&gt;minSpacing&lt;/span&gt;</span>"></Declaration></div>

### handoffDetectRadius

<div><Declaration modifier="public float" content=" <span>&lt;span class=&quot;field&quot;&gt;handoffDetectRadius&lt;/span&gt;</span>"></Declaration></div>

### gizmoSphereRadius

<div><Declaration modifier="public float" content=" <span>&lt;span class=&quot;field&quot;&gt;gizmoSphereRadius&lt;/span&gt;</span>"></Declaration></div>

### items

<div><Declaration modifier="protected readonly List&amp;lt;&lt;a href=&quot;#/api/IndustrialValley.Conveyors/ConveyorItem&quot; title=&quot;ConveyorItem&quot; class=&quot;inherit-link&quot;&gt;ConveyorItem&lt;/a&gt;&amp;gt;" content=" <span>&lt;span class=&quot;field&quot;&gt;items&lt;/span&gt;</span>"></Declaration></div>

## Methods

### InsertItem

Adds a new item to this belt, placing its visual at startPoint (progress = 0).

<div><Declaration modifier="public void" content=" <span>&lt;span class=&quot;method&quot;&gt;InsertItem&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Conveyors/ConveyorItem&quot; title=&quot;ConveyorItem&quot; class=&quot;inherit-link&quot;&gt;ConveyorItem&lt;/a&gt;&lt;/span&gt; item)</span>"></Declaration></div>

### CanAcceptItem

<div><Declaration modifier="public override bool" content=" <span>&lt;span class=&quot;method&quot;&gt;CanAcceptItem&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Conveyors/ConveyorItem&quot; title=&quot;ConveyorItem&quot; class=&quot;inherit-link&quot;&gt;ConveyorItem&lt;/a&gt;&lt;/span&gt; item)</span>"></Declaration></div>

### GetInputPositions

Returns an array of all world‐space input positions for this conveyor.
		     For a belt, that is exactly one position: startPoint.position.

<div><Declaration modifier="public List&amp;lt;&lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/Vector3.html&quot; title=&quot;Vector3&quot; class=&quot;inherit-link&quot;&gt;Vector3&lt;/a&gt;&amp;gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;GetInputPositions&lt;/span&gt;()</span>"></Declaration></div>

### GetOutputPositions

Returns an array of all world‐space output positions for this conveyor.
		     For a belt, that is exactly one position: endPoint.position.

<div><Declaration modifier="public List&amp;lt;&lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/Vector3.html&quot; title=&quot;Vector3&quot; class=&quot;inherit-link&quot;&gt;Vector3&lt;/a&gt;&amp;gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;GetOutputPositions&lt;/span&gt;()</span>"></Declaration></div>

### OnUpdate

<div><Declaration modifier="protected override void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnUpdate&lt;/span&gt;()</span>"></Declaration></div>

### OnLoad

<div><Declaration modifier="public override void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnLoad&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Saving/SaveableData&quot; title=&quot;SaveableData&quot; class=&quot;inherit-link&quot;&gt;SaveableData&lt;/a&gt;&lt;/span&gt; data)</span>"></Declaration></div>

### OnSave

<div><Declaration modifier="public virtual &lt;a href=&quot;#/api/IndustrialValley.Saving/SaveableData&quot; title=&quot;SaveableData&quot; class=&quot;inherit-link&quot;&gt;SaveableData&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;OnSave&lt;/span&gt;()</span>"></Declaration></div>

### OnSell

Called when the buildable has been sold.

<div><Declaration modifier="public virtual void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnSell&lt;/span&gt;()</span>"></Declaration></div>
