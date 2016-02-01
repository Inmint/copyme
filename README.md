# copyme
Jquery Plugin for copy the entire Textarea

  
<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.0/jquery.min.js"></script> 
<script src='/copyme.js'></script>
Example:

<form>
    <textarea id='text1' class="text2"></textarea>
</form>

<button id='mine'>COPY</button>


<script>
$(document).ready(function(){
  $('button').click(function(){
      $('#text1').copyme();
  });
})
</script>

$('#text1').copyme(); 

text1 is textarea/textfield.

Invoke this under onlick or onchange :)

You can easily understand the coding inside the copyme.js file.
You can change the notification or add the css for your alert message by using id 'success-alert'

Example:
$('#success-alert').css('color','blue');
