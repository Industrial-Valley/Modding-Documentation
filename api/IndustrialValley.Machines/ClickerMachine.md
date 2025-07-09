<p class="title">ClickerMachine<span> : <a href="#/api/IndustrialValley.Machines/BaseMachine" title="BaseMachine" class="inherit-link">BaseMachine</a></span><p>

## Fields

### itemToSpawn

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Data/ItemData&quot; title=&quot;ItemData&quot; class=&quot;inherit-link&quot;&gt;ItemData&lt;/a&gt;" content=" <span>&lt;span class=&quot;field&quot;&gt;itemToSpawn&lt;/span&gt;</span>"></Declaration></div>

### detectRadius

<div><Declaration modifier="public float" content=" <span>&lt;span class=&quot;field&quot;&gt;detectRadius&lt;/span&gt;</span>"></Declaration></div>

### visualButton

<div><Declaration modifier="public &lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/Transform.html&quot; title=&quot;Transform&quot; class=&quot;inherit-link&quot;&gt;Transform&lt;/a&gt;" content=" <span>&lt;span class=&quot;field&quot;&gt;visualButton&lt;/span&gt;</span>"></Declaration></div>

### audioSource

<div><Declaration modifier="public &lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/AudioSource.html&quot; title=&quot;AudioSource&quot; class=&quot;inherit-link&quot;&gt;AudioSource&lt;/a&gt;" content=" <span>&lt;span class=&quot;field&quot;&gt;audioSource&lt;/span&gt;</span>"></Declaration></div>

### clickSound

<div><Declaration modifier="public &lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/AudioClip.html&quot; title=&quot;AudioClip&quot; class=&quot;inherit-link&quot;&gt;AudioClip&lt;/a&gt;" content=" <span>&lt;span class=&quot;field&quot;&gt;clickSound&lt;/span&gt;</span>"></Declaration></div>

### clickCooldown

<div><Declaration modifier="public float" content=" <span>&lt;span class=&quot;field&quot;&gt;clickCooldown&lt;/span&gt;</span>"></Declaration></div>

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

### CanAcceptItem

<div><Declaration modifier="public override bool" content=" <span>&lt;span class=&quot;method&quot;&gt;CanAcceptItem&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Conveyors/ConveyorItem&quot; title=&quot;ConveyorItem&quot; class=&quot;inherit-link&quot;&gt;ConveyorItem&lt;/a&gt;&lt;/span&gt; item)</span>"></Declaration></div>

### OnUpdate

<div><Declaration modifier="protected override void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnUpdate&lt;/span&gt;()</span>"></Declaration></div>

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

### OnSave

<div><Declaration modifier="public virtual &lt;a href=&quot;#/api/IndustrialValley.Saving/SaveableData&quot; title=&quot;SaveableData&quot; class=&quot;inherit-link&quot;&gt;SaveableData&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;OnSave&lt;/span&gt;()</span>"></Declaration></div>

### OnLoad

<div><Declaration modifier="public virtual void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnLoad&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Saving/SaveableData&quot; title=&quot;SaveableData&quot; class=&quot;inherit-link&quot;&gt;SaveableData&lt;/a&gt;&lt;/span&gt; data)</span>"></Declaration></div>

### FindClosestDownstreamConveyor

Round‐robin through each output gizmo + center:
		     1) Tries OverlapSphere at each position.
		     2) If that finds none, tries distance-based fallback from that position.
		     Advances nextOutputIndex whenever a handoff is successful.

<div><Declaration modifier="protected &lt;a href=&quot;#/api/IndustrialValley.Conveyors/IConveyor&quot; title=&quot;IConveyor&quot; class=&quot;inherit-link&quot;&gt;IConveyor&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;FindClosestDownstreamConveyor&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Conveyors/ConveyorItem&quot; title=&quot;ConveyorItem&quot; class=&quot;inherit-link&quot;&gt;ConveyorItem&lt;/a&gt;&lt;/span&gt; item)</span>"></Declaration></div>

### OnItemInserted

<div><Declaration modifier="protected virtual void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnItemInserted&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Conveyors/ConveyorItem&quot; title=&quot;ConveyorItem&quot; class=&quot;inherit-link&quot;&gt;ConveyorItem&lt;/a&gt;&lt;/span&gt; item)</span>"></Declaration></div>

### OutputItem

<div><Declaration modifier="protected virtual bool" content=" <span>&lt;span class=&quot;method&quot;&gt;OutputItem&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Conveyors/ConveyorItem&quot; title=&quot;ConveyorItem&quot; class=&quot;inherit-link&quot;&gt;ConveyorItem&lt;/a&gt;&lt;/span&gt; item)</span>"></Declaration></div>
