<p class="title">Inventory</p>

## Events


### OnInventoryUpdated

Event that is triggered when an item is added or removed from the inventory.

<div><Declaration modifier="public delegate void" content=" <span>&lt;span class=&quot;delegate&quot;&gt;InventoryUpdateHandler&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Machines/Inventory.InventorySlot&quot; title=&quot;Inventory.InventorySlot&quot; class=&quot;inherit-link&quot;&gt;InventorySlot&lt;/a&gt;&lt;/span&gt; slot, &lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Machines/InventoryUpdateType&quot; title=&quot;InventoryUpdateType&quot; class=&quot;inherit-link&quot;&gt;InventoryUpdateType&lt;/a&gt;&lt;/span&gt; updateType)</span>"></Declaration></div>
<div><Declaration modifier="public event InventoryUpdateHandler" content=" <span>&lt;span class=&quot;event&quot;&gt;OnInventoryUpdated&lt;/span&gt;</span>"></Declaration></div>

## Properties


### MaxSlots
The maximum number of unique items that can be stored in the inventory.

<div><Declaration modifier="public int" content=" <span>&lt;span class=&quot;property&quot;&gt;MaxSlots&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; &lt;span class=&quot;method&quot;&gt;set&lt;/span&gt;; }</span>"></Declaration></div>

### Slots
The list of items in the inventory.

<div><Declaration modifier="public List&amp;lt;&lt;a href=&quot;#/api/IndustrialValley.Machines/Inventory.InventorySlot&quot; title=&quot;Inventory.InventorySlot&quot; class=&quot;inherit-link&quot;&gt;InventorySlot&lt;/a&gt;&amp;gt;" content=" <span>&lt;span class=&quot;property&quot;&gt;Slots&lt;/span&gt; { &lt;span class=&quot;method&quot;&gt;get&lt;/span&gt;; }</span>"></Declaration></div>

## Methods

### Clear

Clears the inventory, removing all items.

<div><Declaration modifier="public void" content=" <span>&lt;span class=&quot;method&quot;&gt;Clear&lt;/span&gt;()</span>"></Declaration></div>

### Add

Adds an item to the inventory.

<div><Declaration modifier="public bool" content=" <span>&lt;span class=&quot;method&quot;&gt;Add&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Data/ItemData&quot; title=&quot;ItemData&quot; class=&quot;inherit-link&quot;&gt;ItemData&lt;/a&gt;&lt;/span&gt; item, &lt;span class=&quot;param&quot;&gt;int&lt;/span&gt; quantity = 1)</span>"></Declaration></div>

### HasSpace

If the inventory has space for the specified item and quantity.

<div><Declaration modifier="public bool" content=" <span>&lt;span class=&quot;method&quot;&gt;HasSpace&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Data/ItemData&quot; title=&quot;ItemData&quot; class=&quot;inherit-link&quot;&gt;ItemData&lt;/a&gt;&lt;/span&gt; item, &lt;span class=&quot;param&quot;&gt;int&lt;/span&gt; quantity = 1)</span>"></Declaration></div>

### Remove

Removes an item from the inventory.

<div><Declaration modifier="public bool" content=" <span>&lt;span class=&quot;method&quot;&gt;Remove&lt;/span&gt;(&lt;span class=&quot;param&quot;&gt;&lt;a href=&quot;#/api/IndustrialValley.Data/ItemData&quot; title=&quot;ItemData&quot; class=&quot;inherit-link&quot;&gt;ItemData&lt;/a&gt;&lt;/span&gt; item, &lt;span class=&quot;param&quot;&gt;int&lt;/span&gt; quantity = 1)</span>"></Declaration></div>

### GetSaveData

<div><Declaration modifier="public List&amp;lt;&lt;a href=&quot;#/api/IndustrialValley.Machines/Inventory.InventorySlotSaveData&quot; title=&quot;Inventory.InventorySlotSaveData&quot; class=&quot;inherit-link&quot;&gt;InventorySlotSaveData&lt;/a&gt;&amp;gt;" content=" <span>&lt;span class=&quot;method&quot;&gt;GetSaveData&lt;/span&gt;()</span>"></Declaration></div>
