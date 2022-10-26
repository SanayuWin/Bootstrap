# Bootstrap

Table Column Options 
https://bootstrap-table.com/docs/api/column-options/



<h3>Modal</h3>

Modal Move
``` JS
$('.modal-dialog').draggable({
    handle: ".modal-header"
});

```

Modal Show 
``` JS
$('ID').fadeOut("fast",function(){
  $(this).modal('hide')
}).fadeIn("fast",function(){
  $(this).modal('show')
});
```

HTML Modal
``` HTML
<div class="modal fade" id="ID">
  <div class="modal-dialog modal-xl" >
      <div class="modal-content">
          <div class="modal-header btn-primary" style="padding:5px;cursor: move;">
              <h5 class="modal-title"><span >Tital</span></h5>
              <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                <span aria-hidden="true">&times;</span>
              </button>
          </div>
          <div class="modal-body" style=" padding-top:5px; padding-bottom:5px;">
            <div id="detail" >
          </div>
      </div>
      <div class="modal-footer  justify-content-between" style="padding:5px;">
            <button type="button" class="btn btn-default btn-sm" data-dismiss="modal" >Close</button>
          </div>
      </div>
  </div>
</div>
```
