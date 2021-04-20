<template>
  <div class="landingpage">
    <form name="contact" method="POST" data-netlify="true"
    data-netlify-honeypot="bot-field">
        <input type="hidden" name="form-name" value="contact">
        <p>
            <label>Your Name: <input type="text" name="name" /></label>   
        </p>
        <p>
            <label>Your Email: <input type="email" name="email" /></label>
        </p>
        <p>
            <label>Message: <textarea name="message"></textarea></label>
        </p>
        <p>
            <button type="submit">Send</button>
        </p>
    </form>
  </div>
</template>

<script>
export default {
  name: 'LandingPage',
  props: {
    msg: String
  },

 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.landingpage {
    margin: 0 auto;
}
</style>
