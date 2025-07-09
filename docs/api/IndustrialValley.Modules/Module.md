<p class="title">Module</p>

## Properties


### Data
<div><Declaration modifier="public T" content=" <span>&lt;span class=&quot;property&quot;&gt;Data&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

## Methods

### OnInitialize

Called when the module is initialized. All modules are initialized before any module is started. All dependencies
		     are injected before this is called, but they won't be initialized yet.

<div><Declaration modifier="public virtual void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnInitialize&lt;/span&gt;()</span>"></Declaration></div>

### OnStart

Called when the module is started. This is called after all modules are initialized.

<div><Declaration modifier="public virtual void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnStart&lt;/span&gt;()</span>"></Declaration></div>

### OnUpdate

This method is called every frame. It is called after all modules have been started.

<div><Declaration modifier="public virtual void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnUpdate&lt;/span&gt;()</span>"></Declaration></div>

### OnFixedUpdate

This method is called every fixed frame-rate frame. It is called after all modules have been started.

<div><Declaration modifier="public virtual void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnFixedUpdate&lt;/span&gt;()</span>"></Declaration></div>

### OnSave

Called when the game is saved. This is called before the game is saved, so you can save any data you need.

<div><Declaration modifier="public virtual void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnSave&lt;/span&gt;()</span>"></Declaration></div>

### OnLoad

Called when the save is loaded. This is called after the game is loaded, so you can load any data you need.

<div><Declaration modifier="public virtual void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnLoad&lt;/span&gt;()</span>"></Declaration></div>

### OnDestroy

Called when the module is destroyed. This is only called if GameManager.DeleteModule() or
		     GameManager.ReplaceModule() is called.

<div><Declaration modifier="public virtual void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnDestroy&lt;/span&gt;()</span>"></Declaration></div>
