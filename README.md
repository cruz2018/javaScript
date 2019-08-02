# javaScript

<script type="text/javascript">
  function postOk() {
    document.forms[0]['pf.ok'].value = 'clicked';
    document.forms[0]['pf.username'].value = document.forms[0]['dname'].value.toLowercase();
    document.forms[0].submit();
  }
  
  function postCancel() {
    document.forms[0]['pf.cancel'].value = 'clicked';
    document.forms[0].submit();
  }
  
  function postOnReturn(e) {
    var keycode;
    if (window.event) keycode = window.event.keyCode;
    else if (e) keycode = e.which;
    else return true;
    
    
  }
  
  

</script>
