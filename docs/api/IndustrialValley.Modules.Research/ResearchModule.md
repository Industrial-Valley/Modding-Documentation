<p class="title">ResearchModule<span> : <a href="#/api/IndustrialValley.Modules/Module" title="Module" class="inherit-link">Module</a></span><p>

## Events


### OnResearchStateChange

<div><Declaration modifier="public delegate void" content=" <span>&lt;span class=&quot;delegate&quot;&gt;ResearchStateChange&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Data/ResearchableData&quot; title=&quot;ResearchableData&quot; class=&quot;inherit-link&quot;&gt;ResearchableData&lt;/a&gt;&lt;/span&gt; data, &lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Modules.Research/ResearchState&quot; title=&quot;ResearchState&quot; class=&quot;inherit-link&quot;&gt;ResearchState&lt;/a&gt;&lt;/span&gt; state)</span>"></Declaration></div>
<div><Declaration modifier="public event ResearchStateChange" content=" <span>&lt;span class=&quot;event&quot;&gt;OnResearchStateChange&lt;/span&gt;</span>"></Declaration></div>

## Properties


### Data
<div><Declaration modifier="public T" content=" <span>&lt;span class=&quot;property&quot;&gt;Data&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

## Fields

### ResearchInProgress

<div><Declaration modifier="public Dictionary&amp;lt;&lt;a href=&quot;#/api/IndustrialValley.Modules.Research/ResearchModule.ResearchData&quot; title=&quot;ResearchModule.ResearchData&quot; class=&quot;inherit-link&quot;&gt;ResearchData&lt;/a&gt;&amp;gt;" content=" <span>&lt;span class=&quot;field&quot;&gt;ResearchInProgress&lt;/span&gt;</span>"></Declaration></div>

### UnlockedResearch

<div><Declaration modifier="public Dictionary&amp;lt;&lt;a href=&quot;#/api/IndustrialValley.Data/.ResearchableData&quot; title=&quot;.ResearchableData&quot; class=&quot;inherit-link&quot;&gt;ResearchableData&lt;/a&gt;&amp;gt;" content=" <span>&lt;span class=&quot;field&quot;&gt;UnlockedResearch&lt;/span&gt;</span>"></Declaration></div>

## Methods

### OnUpdate

This method is called every frame. It is called after all modules have been started.

<div><Declaration modifier="public override void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnUpdate&lt;/span&gt;()</span>"></Declaration></div>

### PurchaseResearch

Purchases a researchable item if it is not already unlocked or in progress.

<div><Declaration modifier="public void" content=" <span>&lt;span class=&quot;method&quot;&gt;PurchaseResearch&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Data/ResearchableData&quot; title=&quot;ResearchableData&quot; class=&quot;inherit-link&quot;&gt;ResearchableData&lt;/a&gt;&lt;/span&gt; researchable)</span>"></Declaration></div>

### StartResearch

Starts researching a researchable item.

<div><Declaration modifier="public void" content=" <span>&lt;span class=&quot;method&quot;&gt;StartResearch&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Data/ResearchableData&quot; title=&quot;ResearchableData&quot; class=&quot;inherit-link&quot;&gt;ResearchableData&lt;/a&gt;&lt;/span&gt; researchable)</span>"></Declaration></div>

### OnLoad

Called when the save is loaded. This is called after the game is loaded, so you can load any data you need.

<div><Declaration modifier="public sealed override void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnLoad&lt;/span&gt;()</span>"></Declaration></div>

### OnSave

Called when the game is saved. This is called before the game is saved, so you can save any data you need.

<div><Declaration modifier="public sealed override void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnSave&lt;/span&gt;()</span>"></Declaration></div>

### OnInitialize

Called when the module is initialized. All modules are initialized before any module is started. All dependencies
		     are injected before this is called, but they won't be initialized yet.

<div><Declaration modifier="public virtual void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnInitialize&lt;/span&gt;()</span>"></Declaration></div>

### OnStart

Called when the module is started. This is called after all modules are initialized.

<div><Declaration modifier="public virtual void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnStart&lt;/span&gt;()</span>"></Declaration></div>

### OnFixedUpdate

This method is called every fixed frame-rate frame. It is called after all modules have been started.

<div><Declaration modifier="public virtual void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnFixedUpdate&lt;/span&gt;()</span>"></Declaration></div>

### OnDestroy

Called when the module is destroyed. This is only called if GameManager.DeleteModule() or
		     GameManager.ReplaceModule() is called.

<div><Declaration modifier="public virtual void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnDestroy&lt;/span&gt;()</span>"></Declaration></div>
