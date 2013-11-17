ResponsivelySassy
=================

  Responsive multi-column framework built built on SaSS for simplicity and adaptability. Five configuration variables are for setting page width, base font size, target class name, maximum columns and desire gutter. Once these two variables are defined, ReponsivelySassy will automatically calculate gutter, width, padding and 'automagically' insert column requires in media queries for all view ports.


SETUP
/* 
*  Responsive Site Configurations  (_configuration.scss)
* */
* 
  //Max page width
  $_getPageWidth: 1140px;              
  
  //Base font in pixels
  $_getFontSize: 16px;             
  
  //Column class name
  $_getClassName: '_setcol';     
  
  //Number of columns
  $_getMaxCols: 5;                
  
  //Column gutter width in pixels
  $_getGutter: 25px;

  
  DEMO
=================
http://jerryhuang.me
