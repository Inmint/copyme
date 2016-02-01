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
$('button').click(function(){
    $('#text1').copyme();
});
</script>

#You can easily understand the coding inside the copyme.js file.
#You can change the notification or add the css for your alert message by using id 'success-alert'

Example:
$('#success-alert').css('color','blue');
     or
#success-alert{
  color: blue;
}
