bootstrap-compiled
==================

bootstrap.css compiled from source.

Check the xs-AB-subdivision branch, to get a new break point 'xs1' at 480px.

This allows stuff like

    <div class="row">
        <div class="col-xs1-6 col-sm-3">box 1 content</div>
        <div class="col-xs1-6 col-sm-3">box 2 content</div>
        <div class="col-xs1-6 col-sm-3">box 3 content</div>
        <div class="col-xs1-6 col-sm-3">box 4 content</div>
    </div>
    
These boxes will be displayed as 1x4 0..479px, 2x2 on 480..767px, 4x1 on 767..*px.
