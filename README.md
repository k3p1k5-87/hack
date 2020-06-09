# hack
(function(jQuery) {     jQuery('.sortable-image img, .sortable-image').css({width:'auto',height:'auto'})     jQuery('.sortable-image img').each( function(e,elem) {         var fixedImg = jQuery(this).attr('src').replace('s.png','.png');         jQuery(this).attr( 'src', fixedImg );     }); })(jQuery);
