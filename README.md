jquery-pluggins
===============

contains jquery pluggins

clearTextField : this function clears the textfield if the textfield is in focus & have the defualt value in it 
& when the text field looses focus & if it is empty, it will add the default value.

eg: 

<form>

  <input type='text' id='username' value='Username' />

</form>

<script type='text/javascript'>

  jQuery('#username').clearTextField('Username'); 
  
</script>


=================================================================

changePasswordType : when textfield si in focus, this function clears the default value & also changes the type fo the textfield to password.
if the textfield is empty & looses focus, the type of the function is changed to text & the default value is added.

eg: 

<form>

  <input type='text' id='password' value='Password' />

</form>

<script type='text/javascript'>

  jQuery('#password').changePasswordType('Password'); 
  
</script>


=================================================================
