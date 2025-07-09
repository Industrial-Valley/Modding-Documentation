<p class="title">Buildable<span> : <a href="https://docs.unity3d.com/6000.1/Documentation/ScriptReference/MonoBehaviour.html" title="MonoBehaviour" class="inherit-link">MonoBehaviour</a></span><p>

## Properties


### SaveId
The unique identifier for this buildable in the save system.

<div><Declaration modifier="public long" content=" <span>&lt;span class=&quot;property&quot;&gt;SaveId&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; }</span>"></Declaration></div>

## Fields

### sizeX

<div><Declaration modifier="public int" content=" <span>&lt;span class=&quot;field&quot;&gt;sizeX&lt;/span&gt;</span>"></Declaration></div>

### sizeZ

<div><Declaration modifier="public int" content=" <span>&lt;span class=&quot;field&quot;&gt;sizeZ&lt;/span&gt;</span>"></Declaration></div>

### buildableData

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Data/BuildableData&quot; title=&quot;BuildableData&quot; class=&quot;inherit-link&quot;&gt;BuildableData&lt;/a&gt;" content=" <span>&lt;span class=&quot;field&quot;&gt;buildableData&lt;/span&gt;</span>"></Declaration></div>

### outline

<div><Declaration modifier="public Outline" content=" <span>&lt;span class=&quot;field&quot;&gt;outline&lt;/span&gt;</span>"></Declaration></div>

## Methods

### GetFootprintOffsets

Returns local‐grid (x,z) offsets that this object will occupy, given its Y rotation
		     snapped to nearest 0°, 90°, 180°, or 270°.

<div><Declaration modifier="public List&amp;lt;&lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/Vector2Int.html&quot; title=&quot;Vector2Int&quot; class=&quot;inherit-link&quot;&gt;Vector2Int&lt;/a&gt;&amp;gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;GetFootprintOffsets&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;int&lt;/span&gt; yRotation)</span>"></Declaration></div>
