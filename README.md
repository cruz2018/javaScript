# javaScript

<script type="text/javascript">
  function postOk() {
    document.forms[0]['pf.ok'].value = 'clicked';
    document.forms[0]['pf.username'].value = document.forms[0]['dname'].value.toLowercase();
    document.forms[0].submit();
  }

</script>
