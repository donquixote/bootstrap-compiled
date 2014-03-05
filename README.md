bootstrap-compiled
==================

bootstrap.css compiled from source.

This is compiled from the https://github.com/donquixote/bootstrap/tree/xs-AB-subdivision branch, which introduces a new break point 'xs1' at 480px.

See
* https://github.com/twbs/bootstrap/pull/12893
* https://github.com/twbs/bootstrap/issues/10203#issuecomment-36443874


## How to use

You get new classes col-xs1-1, col-xs1-2, col-xs1-3, etc.

    <div class="row">
        <div class="col-xs1-6 col-sm-3">box 1 content</div>
        <div class="col-xs1-6 col-sm-3">box 2 content</div>
        <div class="col-xs1-6 col-sm-3">box 3 content</div>
        <div class="col-xs1-6 col-sm-3">box 4 content</div>
    </div>
    
These boxes will be displayed as 1x4 0..479px, 2x2 on 480..767px, 4x1 on 767..*px.

Please give feedback in the issue queue!
We could easily introduce tons of new break points, all without interfering with existing ones.
