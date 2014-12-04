bootstrap-modal-transition
==========================

Some smooth css transition effects to extend **[Bootstrap 3 modals](http://getbootstrap.com/javascript/#modals)**

### Intro

Bootstrap comes with just a simple fade transition for modals display.
If you like having choice, just add 'bootstrap-modal-transition.less' to your Bootstrap 3 LESS project and it will extends modals with these new transitions :

 * zoom
 * newspaper
 * move-horizontal
 * move-from-top
 * unfold-3d
 * zoom-out

In addition, the use of **[modernizr](http://modernizr.com)** will change the unfold-3d transition with a real 3d transform transition on supported browsers.

## Example

Add the **[less](http://lesscss.org)** file to your bootstrap 3 project add compile your code. In the Modal HTML, add the transition you like :

    <div class="modal fade <transition-type>" id="myModalId" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
            ...
            </div>
        </div>
    </div>

Where <transition-type> is your prefered transition. For example, if you want to use the 'unfold-3d' transition, your code will look like this :

    <div class="modal fade unfold-3d" id="myModalId" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
            ...
            </div>
        </div>
    </div>

As you can see, the default 'fade' transition class **has to be preserved** in order to keep the 'transitionEnd' added by the Bootstrap modal javascript. More information about modal dialogs in bootstrap 3 can be found **[here](http://getbootstrap.com/javascript/#modals)**

Enjoy ;)
