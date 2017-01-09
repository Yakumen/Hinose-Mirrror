jQuery(document).ready(function(){
jQuery('.button_1').click(function(){
jQuery('.content_1').fadeIn('slow');
  jQuery('.content_2').fadeOut('fast');
jQuery('.content_3').fadeOut('fast');
jQuery(this).css('background','#ffd09b');
jQuery(this).css('color','#fff');
jQuery('.button_2').css('background','#fff');
jQuery('.button_2').css('color','#ffd09b');
jQuery('.button_3').css('background','#fff');
jQuery('.button_3').css('color','#ffd09b');
return false;
});
jQuery('.button_2').click(function(){
jQuery('.content_1').fadeOut('fast');
  jQuery('.content_2').fadeIn('slow');
jQuery('.content_3').fadeOut('fast');
jQuery(this).css('background','#ffd09b');
jQuery(this).css('color','#fff');
jQuery('.button_1').css('background','#fff');
jQuery('.button_1').css('color','#ffd09b');
jQuery('.button_3').css('background','#fff');
jQuery('.button_3').css('color','#ffd09b');
return false;
});
jQuery('.button_3').click(function(){
jQuery('.content_1').fadeOut('fast');
  jQuery('.content_2').fadeOut('fast');
jQuery('.content_3').fadeIn('slow');
jQuery(this).css('background','#ffd09b');
jQuery(this).css('color','#fff');
jQuery('.button_1').css('background','#fff');
jQuery('.button_1').css('color','#ffd09b');
jQuery('.button_2').css('background','#fff');
jQuery('.button_2').css('color','#ffd09b');
return false;
});
});
