<p class="title">BankModule<span> : <a href="#/api/IndustrialValley.Modules/Module" title="Module" class="inherit-link">Module</a></span><p>

## Properties


### Balance
<div><Declaration modifier="public long" content=" <span>&lt;span class=&quot;property&quot;&gt;Balance&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; }</span>"></Declaration></div>

### BalanceLabel
<div><Declaration modifier="public string" content=" <span>&lt;span class=&quot;property&quot;&gt;BalanceLabel&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; }</span>"></Declaration></div>

### AveragePerMinuteLabel
<div><Declaration modifier="public string" content=" <span>&lt;span class=&quot;property&quot;&gt;AveragePerMinuteLabel&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; }</span>"></Declaration></div>

### Data
<div><Declaration modifier="public T" content=" <span>&lt;span class=&quot;property&quot;&gt;Data&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

## Fields

### startingBalance

<div><Declaration modifier="public long" content=" <span>&lt;span class=&quot;field&quot;&gt;startingBalance&lt;/span&gt;</span>"></Declaration></div>

## Methods

### OnInitialize

Called when the module is initialized. All modules are initialized before any module is started. All dependencies
		     are injected before this is called, but they won't be initialized yet.

<div><Declaration modifier="public override void" content=" <span>&lt;span class=&quot;method&quot;&gt;OnInitialize&lt;/span&gt;()</span>"></Declaration></div>

### AddMoney

Adds (or subtracts) an integer amount.
		     If amount &gt; 0, counts toward total earned for average.

<div><Declaration modifier="public void" content=" <span>&lt;span class=&quot;method&quot;&gt;AddMoney&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;long&lt;/span&gt; amount)</span>"></Declaration></div>

### AddIncome

This method is used to add income to the bank. It will affect the average earnings per minute.

<div><Declaration modifier="public void" content=" <span>&lt;span class=&quot;method&quot;&gt;AddIncome&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;long&lt;/span&gt; amount)</span>"></Declaration></div>

### HasMoney

Checks if the bank has enough money to cover the given amount.

<div><Declaration modifier="public bool" content=" <span>&lt;span class=&quot;method&quot;&gt;HasMoney&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;long&lt;/span&gt; amount)</span>"></Declaration></div>

### SetMoney

Sets the bank's balance to a specific amount.

<div><Declaration modifier="public void" content=" <span>&lt;span class=&quot;method&quot;&gt;SetMoney&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;long&lt;/span&gt; amount)</span>"></Declaration></div>

### SpendMoney

Attempts to spend the given integer amount.
		     Returns true if successful; false if insufficient funds.

<div><Declaration modifier="public bool" content=" <span>&lt;span class=&quot;method&quot;&gt;SpendMoney&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;long&lt;/span&gt; amount)</span>"></Declaration></div>

### GetAveragePerMinute

<div><Declaration modifier="public long" content=" <span>&lt;span class=&quot;method&quot;&gt;GetAveragePerMinute&lt;/span&gt;()</span>"></Declaration></div>

### GetAveragePerMinuteLabel

<div><Declaration modifier="public string" content=" <span>&lt;span class=&quot;method&quot;&gt;GetAveragePerMinuteLabel&lt;/span&gt;()</span>"></Declaration></div>

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
