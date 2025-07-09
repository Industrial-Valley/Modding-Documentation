<p class="title">UIBuilder</p>

## Constructors


### UIBuilder

<div><Declaration modifier="public" content=" <span>&lt;span class=&quot;method&quot;&gt;UIBuilder&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/UIElements.VisualElement.html&quot; title=&quot;VisualElement&quot; class=&quot;inherit-link&quot;&gt;VisualElement&lt;/a&gt;&lt;/span&gt; elem)</span>"></Declaration></div>

## Properties


### Elem
<div><Declaration modifier="public &lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/UIElements.VisualElement.html&quot; title=&quot;VisualElement&quot; class=&quot;inherit-link&quot;&gt;VisualElement&lt;/a&gt;" content=" <span>&lt;span class=&quot;property&quot;&gt;Elem&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; }</span>"></Declaration></div>

## Methods

### Create

Create a new UIBuilder instance with an empty VisualElement.

<div><Declaration modifier="public static &lt;a href=&quot;#/api/IndustrialValley.Helpers/UIBuilder&quot; title=&quot;UIBuilder&quot; class=&quot;inherit-link&quot;&gt;UIBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;Create&lt;/span&gt;()</span>"></Declaration></div>

### Create

Create a new UIBuilder instance with a VisualElement that has the specified class name.

<div><Declaration modifier="public static &lt;a href=&quot;#/api/IndustrialValley.Helpers/UIBuilder&quot; title=&quot;UIBuilder&quot; class=&quot;inherit-link&quot;&gt;UIBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;Create&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; className)</span>"></Declaration></div>

### AddElement

Add a new element to the current VisualElement.

<div><Declaration modifier="public T" content=" <span>&lt;span class=&quot;method&quot;&gt;AddElement&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;T&lt;/span&gt; element, &lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; className = null)</span>"></Declaration></div>

### AddLabel

Add a new Label to the current VisualElement.

<div><Declaration modifier="public &lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/UIElements.Label.html&quot; title=&quot;Label&quot; class=&quot;inherit-link&quot;&gt;Label&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;AddLabel&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; text, &lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; className = null)</span>"></Declaration></div>

### AddImage

Adds a new Image to the current VisualElement.

<div><Declaration modifier="public &lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/UIElements.Image.html&quot; title=&quot;Image&quot; class=&quot;inherit-link&quot;&gt;Image&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;AddImage&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/Texture2D.html&quot; title=&quot;Texture2D&quot; class=&quot;inherit-link&quot;&gt;Texture2D&lt;/a&gt;&lt;/span&gt; image, &lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; className = null)</span>"></Declaration></div>

### AddImage

<div><Declaration modifier="public &lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/UIElements.Image.html&quot; title=&quot;Image&quot; class=&quot;inherit-link&quot;&gt;Image&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;AddImage&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/Sprite.html&quot; title=&quot;Sprite&quot; class=&quot;inherit-link&quot;&gt;Sprite&lt;/a&gt;&lt;/span&gt; image, &lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; className = null)</span>"></Declaration></div>

### StyleAll

Style all elements of type T within the current VisualElement.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers/UIBuilder&quot; title=&quot;UIBuilder&quot; class=&quot;inherit-link&quot;&gt;UIBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;StyleAll&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;void System.Action&amp;amp;lt;T&amp;amp;gt;&lt;/span&gt; styleAction)</span>"></Declaration></div>

### StyleAll

Style all elements with the specified class name within the current VisualElement.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers/UIBuilder&quot; title=&quot;UIBuilder&quot; class=&quot;inherit-link&quot;&gt;UIBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;StyleAll&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;string&lt;/span&gt; className, &lt;span class=&quot;param&quot;&gt;void System.Action&amp;amp;lt;&lt;a href=&quot;https://docs.unity3d.com/6000.1/Documentation/ScriptReference/UIElements.VisualElement.html&quot; title=&quot;VisualElement&quot; class=&quot;inherit-link&quot;&gt;VisualElement&lt;/a&gt;&amp;amp;gt;&lt;/span&gt; styleAction)</span>"></Declaration></div>

### AddUI

Adds another UIBuilder's VisualElement to the current VisualElement.

<div><Declaration modifier="public &lt;a href=&quot;#/api/IndustrialValley.Helpers/UIBuilder&quot; title=&quot;UIBuilder&quot; class=&quot;inherit-link&quot;&gt;UIBuilder&lt;/a&gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;AddUI&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Helpers/UIBuilder&quot; title=&quot;UIBuilder&quot; class=&quot;inherit-link&quot;&gt;UIBuilder&lt;/a&gt;&lt;/span&gt; uiBuilder)</span>"></Declaration></div>
