ext-4-filter-rows
=================

Filter rows for Sencha Grid view -  EXT version 4.2.x

Use plugin :
Add js file :
<script type="text/javascript" src="ext-all.js"></script>
<script type="text/javascript" src="ux/FilterRow/FilterRow.js"></script>
<script>
var filterRow = Ext.create('Ext.ux.grid.FilterRow');
var grid = Ext.create('Ext.grid.Panel', {
        store: store,
        stateful: true,
        stateId: 'stateGrid',
        plugins : [filterRow],
        columns: [
    	...
        ]	
</script>
