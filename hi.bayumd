# hoverblur-zoom-in

<style>
    /*Blur Zoom Hover Effect*/
.main-sections{
    --zoom-in: 1.2;
    --zoom-out: 0.9;
    --hover-background: #792C1A;
}
.main-sections{
    transition: all .5;
}
.main-sections:hover .card-box{
    filter: blur(5px);
    transform: scale(var(--zoom-out));
}
.card-box{
    transform: scale(1);
    transition: all .5s;
}
.card-box:hover{
    transform: scale(var(--zoom-in)) !important;
    z-index: 2;
    filter: blur(0px) !important;
}
.main-sections .elementor-widget-wrap{
    transition: all .5s;
}
.main-sections .card-box:hover .elementor-widget-wrap{
    background: var(--hover-background) !important;
}
</style>
