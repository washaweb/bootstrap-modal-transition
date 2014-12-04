bootstrap-modal-transition
==========================

Some cool css transition effects to use with **[Bootstrap 3 modals](http://getbootstrap.com/javascript/#modals)**

### Intro

Bootstrap comes with a simple fade effect for modals. Just add bootstrap-modal-transiton to your project and it will extends modals with some more cool transitions :

 * zoom
 * newspaper
 * move-horizontal
 * move-from-top
 * unfold-3d
 * zoom-out

If you use **[modernizr](http://modernizr.com)**, the unfold-3d will comme with be set as a real 3d transform transition on supported browsers.

## Example

Add the **[less](http://lesscss.org)** file to your bootstrap 3 project add compile your code. In the Modal HTML, add the transition you like :

    <div class="modal fade <transition-type>" id="myModalId" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
            ...
            </div>
        </div>
    </div>

where <transition-type> is your prefered transition. For example, if you want to use unfold-3d the code will be :

    <div class="modal fade unfold-3d" id="myModalId" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
            ...
            </div>
        </div>
    </div>

More information about modal dialogs in bootstrap 3 can be found **[here](http://getbootstrap.com/javascript/#modals)**
