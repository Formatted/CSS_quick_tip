# CSS_quick_tip

## Static: 
is the default,  positions itself based on the div hierarchy, doesn't listen to top,left,bottom,right (tlbr),z commands

## Relative: 
moves with the tlbr commands depending on their values, child move with them but siblings (divs on same level) stay where they are

## Absolute: 
it by default positions itself to the next ancestor which is relative ( if none relative then body by default is relative) and tblr commands take the relative ancestor as a reference point. again childs will move with it however siblings will deny its existence and position themselves as absolute never existed

## Fixed: 
it just defaults itself to the body and tblr commands take start of the body as the reference point,  Again children will follow and siblings will deny existence. used for navbars
