<template>
  <div class="container">
    <div>
      <h1>Contact Us</h1>
    </div>
    	<div id="contact-form" class="contact-form">
		<form class="form">
			<input required name="name" placeholder="Name" type="text" autocomplete="off">
			<input required name="subject" placeholder="Subject" type="text" autocomplete="off">
			<textarea name="message"  rows="4" placeholder="Message"></textarea>
		   <button class="button">Send</button>
		</form>
	</div>
  </div>
</template>

<script>

</script>

<style>
.contact-form {
	font-family: 16px;
	margin: 0 auto;
	max-width: 1000px;
	width: 100%;
}

.contact-form .form {
	display: flex;
	flex-direction: column;
	font-size: 16px;
}

.contact-form input[type="email"],
.contact-form input[type="text"],
.contact-form textarea {
	border: solid 1px #e8e8e8;
	font-family: 'Roboto', sans-serif;
	padding: 10px 7px;
	margin-bottom: 15px;
	outline: none;
}

.contact-form textarea {
	resize: none;
}

.contact-form .button {
	background: #f91d27;
	border: solid 1px #da552f;
	color: white;
	cursor: pointer;
	padding: 10px 50px;
	text-align: center;
	text-transform: uppercase;
}

.contact-form .button:hover {
	background: #eec22e;
	border: solid 1px black;
}

.contact-form input[type="email"],
.contact-form input[type="text"],
.contact-form textarea,
.contact-form .button {
	font-size: 15px;
	border-radius: 3px
}
</style>
