THE WEBSITE ARCHITECTURE BREAKDOWN FOR QUICK ACCESS:

CSS -> GLOBAL, STYLES

|----------------------- MENU --------------------|
DESKTOP MENU -> container-menu-desktop menu-light menu-sticky
MOBILE MENU  -> container-menu-bar-mobile menu-light menu-sticky 
SLIDE OUT MENU (MOBILE) -> flyout-menu flyout-menu-is-closed menu-light

|----------------------- HERO BLOCK --------------------|
DESKTOP & MOBILE -> container-flexbox container-hero-block-two-columns unhide-content-under-sticky-menu
    (1.) hero-item-1 
    (2.) hero-item-2 
       
FOOTER -> container-footer
    (1.) flex-item-1
    (2.) flex-item-2
    (3.) flex-item-3